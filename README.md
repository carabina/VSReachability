VSReachability
============


VSReachability is a simple Swift protocol extension that checks to see if the device has an internet connection.

NOTE: Only works on devices. This will always return true for the Simulator.

Installation
============


Add VSReachability.swift to your project.


Usage
=====

Have your class conform to the VSReachability protocol.

```
VSReachability
```

Use the convenience method isConnectedToNetwork to check internet connection.

```
if self.isConnectedToNetwork()
{
  print("Connected :)")
}
else
{
  print("Not Connected :(")
}
```
