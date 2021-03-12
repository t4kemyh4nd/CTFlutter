# CTFlutter

## Description
CTFlutter is an Android based CTF with an added layer of Flutter functionality. There are 2 flags to be found. You can download the APK at https://www.dropbox.com/s/ipvlt1260rj4he7/ctflutter.apk?dl=0

## Rules
To learn the most out of this challenge, you should try to follow the below rules:
- No manual invoking of activies using ADB / Drozer allowed
- Yes, both the flags is stored in the app's private directory, simply reading them from a root shell is not the intended way.
- Your goal is to find both the flags using dynamic analysis. You may create a 'malicious' app to interact with the app and get the first flag.

## Challenges included
- SQL injection
- [Attacking proxy activities and file providers](https://blog.oversecured.com/Android-Access-to-app-protected-components/)
- Reversing Flutter source code compiled in debug environment
- Attacking a vulnerable Flutter plugin
