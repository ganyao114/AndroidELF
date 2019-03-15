# AndroidELF
search all symbal in ELF file(dlsym can not find)

dlsym or fake_dlsym can only find dynamic link symbals in SHT_STRTAB

this util is help you to search other symbal(include dynamic link symbals) in SHT_SYMTAB:

example: 

"art_quick_to_interpreter_bridge" in libart.so

# Use

include files:

https://github.com/ganyao114/SandHook/blob/master/hooklib/src/main/cpp/utils/elf_util.cpp
