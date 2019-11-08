# startup-name-generator
Developed a backend using Go for the JS Version of the same. JS Version - https://codepen.io/rstacruz/full/wJyaJb

[![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-go.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-responsibility.svg)](https://forthebadge.com)   
startup-name-generator in Go using go-gin.    


## Instructions 
After all the package setup done, run the `main.go` file.   
The app will run on `localhost:8080`   

### Endpoints 
``` GET - / ```   
Request - nil  
Response -  
``` 
{
    "message": "Running Fine"
}
```

``` GET - /{string} ```   
Response -  
```
{
    "data": {
        "names": [
            "FITDASH",
            "FITTION",
            "ARCRUN",
            "ARCFIT",
            "FITGENT",
            "FITFUL",
            "APPRUN",
            "APPFIT",
            "FITENT",
            "FITER",
            "FITITE",
            "FITICE",
            "CORUN",
            "COFIT",
            "CONRUN",
            "CONFIT",
            "FITANCE",
            "FITUP",
            "CLEARRUN",
            "CLEARFIT",
            "ENRUN",
            "ENFIT",
            "FITYARD",
            "FITWARE",
            "FITVIBE",
            "FITVERGE",
            "FITVIEW",
            "FITTYPE",
            "FAIRRUN",
            "FAIRFIT",
            "GORUN",
            "GOFIT",
            "HIGHRUN",
            "HIGHFIT",
            "FITTURE",
            "FITTILT",
            "INRUN",
            "INFIT",
            "FITTAP",
            "FITSYNC",
            "FITSTORM",
            "FITSTART",
            "JUMPRUN",
            "JUMPFIT",
            "FITSPOT",
            "FITSPARK",
            "FITSPAN",
            "FITSPACE",
            "MASSRUN",
            "MASSFIT",
            "FITSCOPE",
            "FITSNAP",
            "FITSION",
            "FITSIDE",
            "FITSHIP",
            "FITSHIFT",
            "ONRUN",
            "ONFIT",
            "FITSET",
            "FITSENSE",
            "FITSCOUT",
            "FITSCAN",
            "FITSCALE",
            "FITSCAPE",
            "OUTRUN",
            "OUTFIT",
            "FITRISE",
            "REFIT",
            "REALRUN",
            "REALFIT",
            "PEAKRUN",
            "PEAKFIT",
            "FITPUSH",
            "FITPRIME",
            "SHIFTRUN",
            "SHIFTFIT",
            "FITPRESS",
            "FITPOST",
            "FITPORT",
            "FITPASS",
            "SPARKRUN",
            "SPARKFIT",
            "STARTRUN",
            "STARTFIT",
            "TRUERUN",
            "TRUEFIT",
            "UPRUN",
            "UPFIT",
            "FITNOW",
            "FITNESS",
            "RUNARC",
            "FITMARK",
            "RUNBASE",
            "RUNBAY",
            "RUNBOOST",
            "FITMODE",
            "RUNCASE",
            "FITMENT",
            "RUNCAST",
            "RUNCLICK",
            "RUNDASH",
            "RUNDECK",
            "RUNDOCK",
            "RUNDOT",
            "RUNDROP",
            "FITLOOP",
            "RUNFLOW",
            "RUNGLOW",
            "RUNGRID",
            "RUNGRAM",
            "RUNGRAPH",
            "RUNHUB",
            "FITLOAD",
            "RUNKIT",
            "RUNLAB",
            "FITLINE",
            "FITLIGHT",
            "RUNLIGHT",
            "RUNLINE",
            "FITLAB",
            "RUNLOAD",
            "RUNLOOP",
            "RUNMENT",
            "FITKIT",
            "RUNMODE",
            "RUNMARK",
            "RUNNESS",
            "RUNNOW",
            "RUNPASS",
            "RUNPORT",
            "RUNPOST",
            "RUNPRESS",
            "RUNPRIME",
            "RUNPUSH",
            "RUNRISE",
            "RUNSCAPE",
            "RUNSCALE",
            "RUNSCAN",
            "RUNSCOUT",
            "RUNSENSE",
            "RUNSET",
            "RUNSHIFT",
            "RUNSHIP",
            "RUNSIDE",
            "FITGRAPH",
            "RUNSNAP",
            "RUNSCOPE",
            "RUNSPACE",
            "RUNSPAN",
            "RUNSPARK",
            "RUNSPOT",
            "RUNSTART",
            "RUNSTORM",
            "FITGRAM",
            "RUNSYNC",
            "RUNTAP",
            "RUNTILT",
            "RUNTURE",
            "RUNTYPE",
            "RUNVIEW",
            "RUNVERGE",
            "RUNVIBE",
            "RUNWARE",
            "RUNYARD",
            "RUNUP",
            "FITGRID",
            "FITGLOW",
            "RUNANCE",
            "FITFLOW",
            "RUNICE",
            "RUNITE",
            "RUNER",
            "FITDROP",
            "RUNENT",
            "RUNFUL",
            "RUNGENT",
            "RUNTION",
            "RUNSION",
            "FITARC",
            "FITDOT",
            "FITBASE",
            "FITBAY",
            "FITBOOST",
            "FITDOCK",
            "FITCASE",
            "FITDECK",
            "FITCAST",
            "FITCLICK",
            "RERUN",
            "FITHUB",
            "FITIBLE",
            "FITATLAS",
            "AUTOFIT",
            "AVIRUN",
            "RUNIBLE",
            "RUNABLE",
            "RUNARY",
            "RUNSTRIPE",
            "FITLOGIC",
            "AVIFIT",
            "FITFOCUS",
            "BASERUN",
            "RUNLOGIC",
            "FITLEVEL",
            "FITLAYER",
            "RUNLAYER",
            "RUNLEVEL",
            "BASEFIT",
            "RUNFOCUS",
            "AUTORUN",
            "CORERUN",
            "FITABLE",
            "FITARY",
            "RUNATLAS",
            "VIBEFIT",
            "VIBERUN",
            "SOLIDFIT",
            "SOLIDRUN",
            "ONEFIT",
            "COREFIT",
            "PUREFIT",
            "PURERUN",
            "ECHORUN",
            "OVERFIT",
            "OVERRUN",
            "OPENFIT",
            "OPENRUN",
            "EVERFIT",
            "ONERUN",
            "OMNIFIT",
            "OMNIRUN",
            "ECHOFIT",
            "EVENRUN",
            "METAFIT",
            "METARUN",
            "MAKEFIT",
            "EVENFIT",
            "LIVEFIT",
            "LIVERUN",
            "ISOFIT",
            "ISORUN",
            "FITSTRIPE",
            "INTERFIT",
            "INTERRUN",
            "HYPERFIT",
            "HYPERRUN",
            "MAKERUN",
            "EVERRUN",
            "FITENGINE",
            "MATTERRUN",
            "MATTERFIT",
            "FITCAPSULE",
            "SILVERRUN",
            "RUNCAPSULE",
            "FITMETHOD",
            "RUNCENTER",
            "RUNENGINE",
            "FITCENTER",
            "RUNMETHOD",
            "FITSIGNAL",
            "SILVERFIT",
            "RUNSIGNAL",
            "FITEON",
            "RUNEON",
            "ACTIVERUN",
            "ACTIVEFIT"
        ]
    },
    "status": 200,
    "message": "Success"
}
``` 

## Other Notes   
There were a lot of projects running on my GoLand IDE. You may have to reconfigure few of the packages on your own. :confused:

## Contribute 
Want to contribute? Great
