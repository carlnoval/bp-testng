# Boiler Plate: TestNG project
## Requirements
- Java LTS 17
## What comes with this project
- Basic boiler plat for a TestNG project
## Things to watch out for
- Web Driver versions
- POM (project object model) hell
## Things to do when creating a new repo out of this boiler plate
1. Delete the `.git` folder in root
2. Update project folder's name
3. Update artifactId in `pom.xml`
   - Using the same name as the project folder would be nice
4. Update `<module name="bp-testng" />` in `bp-testng/.idea/compiler.xml` to the proper project name
## Does not come with any of the following
- reporting
- github actions
- testng.xml file
- dockerization
- selenium grid
