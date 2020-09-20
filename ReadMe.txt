#---------------------------------------------------
# Build process:
#   1. add source files to project directories 
#   2. add CMakeLists.txt (this file)
#   3. mkdir build                 - this puts intermediate
#   4. cd build                      files in build directory
#   5. cmake ..                    - create cmake config files
#   6. cmake --build . --config Release
#   7. "./Release/HelloCmake.exe"  - runs executable 
#   8. Notes:
#      - you can change any of the source files then: 
#          cmake --builid . --config Release
#          "./Release/HelloCmake.exe
#      - delete build directory to clean
#          cmake will regenerate it
#   9. Note: 
#      - you can substitute debug for release 
#        in contents of 8.
#---------------------------------------------------
