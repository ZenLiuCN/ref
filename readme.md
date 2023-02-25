# Ref the reflection utils

## Functions

+ Type : utility interface for reflect operation on Classes
+ Prop : utility interface for reflect operation on Fields
+ Func : utility interface for reflect operation on Methods
+ Creator : utility interface for reflect operation on Constructors
+ Handle : utility interface for reflect operation on MethodHandles
+ Generate : container interface with methods to generate wrap interface utility

+ $.version: constant jvm version
+ $.BoxType: map of boxed types to primitive types
+ $.UnboxType: map of boxed types to primitive types
+ $.access(): hacking access to Reflect elements
+ $.declared(): found declared constructor
+ $.openModules(): hacking way open module for all
+ $.methods(): fetch all methods from class/interface
+ $.fields(): fetch all fields from class
+ $.constructors(): fetch all constructors from class
+ $.declaredClasses(): fetch all declaredClasses from class

## Notes

1. Support jdk 1.8+ version
2. Internal use [Caffeine](https://github.com/ben-manes/caffeine) for cache, choose your runtime version based on jvm
   version.