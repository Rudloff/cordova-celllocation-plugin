cordova-celllocation-plugin
===========================

Cordova plugin to access GSMCellLocation on Android


Install
======

    cordova plugin add https://github.com/Rudloff/cordova-celllocation-plugin.git


Usage
=====

    cellLocation.get(function (result) {
        var cell = JSON.parse(result);
        console.log('Cell ID: ' + cell.CID);
    }, function () {
        console.log("error");
    });


Credits
=====
This project includes some code from https://github.com/vliesaputra/DeviceInformationPlugin
