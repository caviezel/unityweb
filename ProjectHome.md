The WWW class in Unity3D is deficient in many ways.

Unity3D WebPlayer and iOS builds cannot use System.Net.WebRequest due to security concerns. The solution? Write a HTTP class from scratch, based on plain old sockets.