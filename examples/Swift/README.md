# iOS Swift Example app


Xcode project for developing a MEGA app for iOS.

Target OS: iOS 7.0

Demo application that allows:

- Login into user account

- List folders and files stored into the user account

- Navigate along the folders structure (forward and backward)

- Download files

- Delete, rename and export nodes

- View contacts

- Logout

## How to build and run the project:

To build and run the project, follow theses steps:

1. Download or clone the whole SDK

2. Download the prebuilt third party dependencies from this link: https://mega.nz/#!QF02zQTL!rdyWnXtY3utfyuMdWCmpoR9CXHPGKQpf1afXQenk5vI

3. Uncompress the content and move `include`and `lib`to the directory `sdk/bindings/ios/3rdparty`

4. Go to `sdk/examples/Swift` and open `MEGAWS.xcworkspace`

5. Make sure the `MEGA` target is selected

6. Build and run the application

If you want to build the third party dependencies by yourself: open a terminal in the directory `sdk/bindings/ios/3rdparty`. Run	`sh build-all.sh` (Wait until the process ends, it will take some minutes ~20)
