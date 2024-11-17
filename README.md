
## Source Code? This GSI based on ponces Android 15 AOSP

## Build

To get started with building AOSP GSI, you'll need to get familiar with [Git and Repo](https://source.android.com/docs/setup/reference/repo) as well as [How to build a GSI](https://github.com/phhusson/treble_experimentations/wiki/How-to-build-a-GSI%3F)

Note: 
- Pay attention to number 1 - 5
- You need at least 30 GB of RAM to build this
- At least 200 Free storage (HDD or SSD)
- There is a note (Notes.txt) That contains bootanim logo and default wallpaper path, and also system.img path. Hope it helps
- Pay attention to the KLC_OS/treble_aosp/build.sh script. I also write something there
- All KLC OS Files are inside KLCStuffs folder

### Steps

1. Create a new working directory for your AOSP build and navigate to it: <br />
`mkdir rising_os; cd rising_os`

2. Clone this repo: <br />
`git clone https://github.com/Ghostca1n/Rising_OS_GSI -b android15.0`

3. Start the build, Good luck. <br /> 
`bash rsing_OS/treble_aosp/build.sh`

Thanks to:
- [ponces](https://github.com/ponces)
- TrebleDroid Builders Community
- Wahid (Lend me a Server)
