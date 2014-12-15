# How to Recompile (Linux)

```
# Make modifications to .lua files in /src
vim /src/main.lua

# Zip up game files into a Love archive
cd src/
zip -9 -q -r ../03.love .

# Update Love resource
cp 03.love build/osx/03.app/Contents/Resources/

# Zip up app directory into distributable
cd build/osx/
zip -9 -q -r 03.zip 03.app/
```
