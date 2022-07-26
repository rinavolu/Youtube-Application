<h1 align="center"><img align="center" src="https://github.com/rinavolu/Youtube-Application/blob/master/assets/icons/youtube-icon.png" width="45" align="left"> Unoffical Youtube Application</h2>
<p align="center">
  <em>
    Standalone Application
    · Platform compatibility
    . AdBlocker
    · JavaScript
    · TypeScript
    . Electron
  </em>
</p>

## About The Project
This is a simple youtube desktop application built using electron. Easy to use on any platform and integrated with an adblocker.

## Releases
<table>
  <thead>
    <tr>
      <th>Version</th>
      <th>Release Date</th>
      <th>Download Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.0.0</td>
      <td>26-07-2022</td>
      <td>
        <a href="https://drive.google.com/drive/folders/174ewRbnEoMsf82qeDdj6MogRQ5ptP6Gq?usp=sharing">View</a></td>
    </tr>
  </tbody>
</table>

## Project Setup And Release
Follow these steps to setup this project in your local,
1. Clone this repository using `git clone https://github.com/rinavolu/Youtube-Application.git`
2. Open terminal in the working directory and execute `npm install` to install node modules
3. Run this command to start application using `npm start`

Horray by this time you are able to run application in your machine 🎉.

If adblocker lib is not installed use `npm install --save @cliqz/adblocker-electron`.
If ts-node and cross-fetch modules were not installed use `npm i ts-node` and `npm i cross-fetch`.


To release a version we need electron packager `npm install electron-packager cross-var --save-dev`. After installing we can use 

`npm run package-all` -  to release a version for all platforms

`npm run package-win` -  to release a version for windows

`npm run package-linux` - to release a version for linux

`npm run package-mac` or `npm run package-osx` - to release a version for mac

## Standalone Application
Please use below download links to download latest application version
<ol>
  <li>Windows Installer</li>
  <li>Windows Zip</li>
  <li>Mac</li>
</ol>

## Application Dependencies
<table>
  <thead>
    <tr>
      <th>Dependency</th>
      <th>Version</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Electron</td>
      <td>19.0.9</td>
    </tr>
    <tr>
      <td>Electron-packager</td>
      <td>15.5.1</td>
    </tr>
    <tr>
      <td>Cross-var</td>
      <td>1.1.0</td>
    </tr>
    <tr>
      <td>Concurrently</td>
      <td>7.3.0</td>
    </tr>
  </tbody>
</table>


## Application Screenshots
Windows 11
![](https://i.ibb.co/N6t2Xfh/windows11src.png)
![](https://i.ibb.co/fdK6vVR/windows11src2.png)

## AdBlocker
We are using adblockers from [Ghostery](https://www.ghostery.com/) and [Cliqz](https://cliqz.com/). This library is easy to use and built on javascript for blocking ads. 
For more information about Cliqz's Adblocker please refer [Cliqz Adblocker](https://github.com/ghostery/adblocker.git).

## Future Implementations
- Need to add navigation 
- Add tabs
- Integrate chrome Adblocker extensions to block ads more efficiently


## Issues
- Sometimes observing an ad at start of the video
- No navigation buttons

For any question, feel free to [open an issue ](https://github.com/rinavolu/Youtube-Application/issues/new) or a pull request to get some help!

## Note
I'm new to electronJs. Feel free to suggest if any features can be integrated. I'll try my best to add more features to this application.
Thank you so much for going through this project ❤️
