# Rayblib Project

### Includes Raylib 4.5, both shared object and static libraries.
* My goal with this is to create a base which compiles on both Windows and Linux based systems
* Why? Because sometimes I'm too lazy revire everything into my laptop.

### Issue(s)
* For some reason static linking wasn't possible, hence the inclusion of shared object libraries.
* Windows libraries aren't included, I might learn CMake/Freemake to make the project cross-platform, or make a VS solution for it.
