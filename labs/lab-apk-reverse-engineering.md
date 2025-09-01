# Lab – APK Reverse Engineering

## Objective
Analyze an Android APK to identify hardcoded credentials and insecure coding practices.

## Steps
1. Obtain a sample APK (test app).  
2. Use `apktool` to decompile the APK.  
3. Inspect `AndroidManifest.xml` for permissions.  
4. Check for hardcoded API keys in `.smali` files.  
5. Document findings.  

## Tools
- Apktool  
- jadx (Java decompiler)  
