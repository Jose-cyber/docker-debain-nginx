## building a docker  container with debian and nginx

in this small project, i created a dockerfile that provides a debian container and installs nginx

### required commands: 

**docker build -t [name]/img:1.0 .**

**docker container run -d -p 8080:80 [name]/img:1.0** 
