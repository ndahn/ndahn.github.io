# Rocksi
Rocksi is the R**obot** Bl**ock**s **Si**mulator. Acronyms are strange :)

Rocksi is a robot simulator that runs entirely in (modern) web browsers with absolutely no installation. It is thus platform independent and won't care if students are working on Android tablets, iPads or laptops. The robot is programmed using the popular [Blockly](https://developers.google.com/blockly/ library, which is also used by Scratch, Niryo, and a bunch of other projects, and a custom execution routine. 

A running version can be found **[rocksi.net](https://rocksi.net)**!
The source code is available on github at **[github.com/ndahn/Rocksi](https://github.com/ndahn/Rocksi)**!


## License
Rocksi is distributed under the very permissive MIT license, which basically states that you can do with it whatever you want! Check out the LICENSE file for further details. However, please be aware that some of the robot models included may use different licenses. The relevant companies have permitted the use in Rocksi.


## Building
You will need [npm](https://www.npmjs.com/) or any other package manager that can handle `package.json` files to build this project. First install the dependencies by running the following command in the project's root directory:
```
npm install
```

Afterwards you can build the project in development or build mode by running
```
npm run [dev|build]
```

This will also start a local parcel webserver serving Rocksi. Especially when running in `build` mode, check the `scripts` section in package.json as it may contain some settings that influence the build process.


## Motivation
Robots are one of the corner stones of future industries and technological development. The recent years' advancements in control, intuivity and sensitivity has made these beautiful yet complex machines much more accessible. Modern robots manage to hide much of their complexity, to the degree that even non-specialists and children can handle them with ease. 

Despite these major advancements, to the average person robots stay elusive and incomrpehensible, almost mystical. This is for two reasons:
* they are expensive and hard to come by
* the knowledge and tech that makes them move is non-trivial and inaccessible

To this end many schools throughout the world have started adding robotics to their curricula. However, their expensive nature gave rise to a new problem: at classes of 20-40 students, how can every student work with the robot if the school can't afford to spend hundreds of thousands of euros? This is where Rocksi comes in!


## Further Reading
If you speak German and want to learn more about robotics, I want to highlight the free **Roboterführerschein** (robots driving license) on [robotikschulungen.de](https://robotikschulungen.de), which I co-developed. Hint: the Niryo courses are by me as well :)
