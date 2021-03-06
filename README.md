# react-monocle
[![Build Status](https://travis-ci.org/team-gryff/react-monocle.svg?branch=master)](https://travis-ci.org/team-gryff/react-monocle) [![npm version](https://badge.fury.io/js/react-monocle.svg)](https://badge.fury.io/js/react-monocle)

<img src="react/assets/logo.png" width="300"/>

</br>
**React Monocle** is a developer tool for generating visual representations of your React app's component hierarchy.

</br>
<img src="demo.gif" width="600"/>

## How It Works
React Monocle parses through your React source files to generate a visual tree graph representing your React component hierarchy. 
The tree is then displayed along with a live copy of your application. 
The rendered tree is synced up to the state(s) of your component using Redux, and as the state of your live app changes, the monocle tree graph will also provide visual feedback of data flow and state changes through the React components.

## Setup
1. ```npm install -g react-monocle```
2. Navigate to the directory which contains your html file.
3. Run ```monocle -c <html> -b <bundle>```, where html and bundle are the relative paths to your html and bundle files (only works on bundles that have not been mangled/minified).
4. If more options are needed (ie if your React files are written in .js instead of .jsx), type ```monocle -h``` for more available options.

## Options
```
-e, --entry <entry>: App entry point. Defaults to JSX file where ReactDOM.render is found.
-d, --directory <directory>: directory of React files. Defaults to where Monocle was called.
-j, --extension <extension>: extension of React files (jsx or js). Defaults to .jsx (only use when specifying/in directory which has your React files!)
```
## Our Team
* Michael-Bryant Choa - [github.com/mbchoa](https://github.com/mbchoa)
* Jenna Davis - [github.com/jdavis218](https://github.com/jdavis218)
* Jerry Mao - [github.com/jerrymao15](https://github.com/jerrymao15)

## License
MIT

