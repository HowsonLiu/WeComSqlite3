# WeCom Sqlite3
A solution of database encryption used by WeCom

# Build
1. Download premake5
2. cd to root path
3. premake5 vs2019
4. open .sln file
5. build all

# How to use
1. copy src/sqlite3.h file to your project
2. link sqlite3.lib or sqlite3.dll 
3. hook the password in WeCom
4. use sqlite3_open and sqlite3_key to open and decrypt wecom's database
5. enjoy it:)