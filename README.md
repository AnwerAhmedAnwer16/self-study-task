# self-study-task
1. **locate vs find**  
   - locate is a fast search tool because it uses a pre-built database. Just type locate filename and it shows results instantly. However, results might be outdated if the database wasn't updated recently   
   - find is slower but more powerful because it searches the actual filesystem. You can search by name, size, type, modification date etc. 

2. **apt vs dpkg vs yum vs rpm**  
   - apt is the main package manager for Debian/Ubuntu. It handles dependencies automatically and downloads packages from online repositories. 
   - dpkg is the low-level tool for installing .deb files in Debian systems. It doesn't resolve dependencies.  
   - yum is like apt but for RedHat/CentOS systems. It manages dependencies and downloads packages.  
   - rpm is the low-level installer for .rpm files in RedHat systems. Like dpkg, it doesn't handle dependencies. 
3. **conclusion**  
   - locate is faster but less accurate, find is slower but more precise  
   - apt/yum are high-level tools that handle dependencies  
   - dpkg/rpm are low-level tools that work with local files  
   - apt/dpkg are for Debian systems, yum/rpm are for RedHat systems  

