# YudizFramework
Developing your own swift framework has below benefits.
1. Reusable code 
2. Secure or Hide your code. 
3. Reduce recompilation  
4. Save time 

### NOTE:
Please add below in your project's Run Script (Project Target -> Build Phase -> Add Run Script)
```
bash "${BUILT_PRODUCTS_DIR}/${FRAMEWORKS_FOLDER_PATH}/YudizFramework.framework/ios-framework-build.sh" YudizFramework
```

Without above script you will face issue when uploading app to App Store as what we just made is Universal framework and Apple does not allow extra architectures.
