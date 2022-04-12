# Parcel 

You can setup a hot environment by Parcel, even if you change anything parcel will change it automatically

## Install Parcel in a  project directory

1. first install npm package

```npm init -y```

2. Then add html file 

3. run command ```npx parcel index.html```

## If index.html have in src folder, then 

1. in packages.json

```"script": "parcel index.html"```

then run **npm start** 

then **index.html** file will be hot reload again

2. If we add **wtach flag** then, it will automatically changes when we changes our source file

```"script": "parcel watch index.html"```

# For more check [Parcel Doc](https://parceljs.org/docs/)
