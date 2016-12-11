# migraine
The migraine project is a toolset for developing for ecma platforms, consisting of migration tools, compilers and polyfills.

"migraine" is an acronym for Migration Implementation Notation for ECMA (or maybe you can suggest a better acronym?  I just like it as a word.)

It (will) consist of:
* source to source compilers for migration between different versions of ECMA;
* source to native/target platform application compilers;
* polyfill installers and managers;
* plugins and editor syntax highlighters for popular IDEs.

Currenty migraine is seperated into 5 sub-projects, namely:
* migraine-ecmam               - source to source migration tool;
* migraine-ecmac               - source to native/target platform compiler;
* migraine-polyfill            - run-time polyfills with runtime installers and a manager tool
* migraine-polyfill-manager    - a polyfill manager tool
* migraine-ide                 - an set of populAR IDE syntax highlights and plugins

The migraine project and sub-projects are all licensed under the MIT license.

Coding standards for these project vary slightly depending on the language they are writen in, but follow these general rules:
* codes lines must not exceed 80 characters;
* * strings and encapsulated lines should be broken with an efficient concation method;
* * line continuations must be double indented.
* argument and declarations list must be seperated where the seperator resides on the continuation line;
* variable declarations must be at the beginning of their scope blocks unless they are specifically required y their function elsewhere;
* documentation comments must be implemented for all globals, function, function & method arguments, classes, properties, methods, constructors, and destructors.

For more information check this projects documentation page and the sub projects.

For the license, check the LICENSE.md file included with this project and sub projects.  They are all under the MIT license.

To support these projects please donate or become a contributor.
+ Information on donations can be found here;
+ Unformation on becoming a contributor can be found here.  We especially welcome coders, profilers, documention editors, marketing and media professionals, project managers and code reviewers.  It would be really great if we had a few people from the platform projects (ecma, w3c, node, AMD, chrome, mozila, apple, opera, etc...)



