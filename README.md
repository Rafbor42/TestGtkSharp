# TestGtkSharp
This is a simple .NET GtkSharp app to test Snap packaging 

## How to create a Snap

1. Clone this repository.
2. Build the Snap package with:
```
$ snapcraft --debug
```
  - `--debug` enables you to view logs within the environment, check the value of environment variables, locate missing binaries and install missing dependencies.
3. Install the Snap on your system with:
```
$ sudo snap install testgtksharp_0.1_amd64.snap --devmode --dangerous
```
4. Run the app:
```
$ testgtksharp
```
