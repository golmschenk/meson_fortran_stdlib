project('meson_fortran_stdlib', 'fortran')

fortran_compiler = meson.get_compiler('fortran')

cmake = import('cmake')

fortran_stdlib = cmake.subproject('fortran_stdlib')
fortran_stdlib_dependency = fortran_stdlib.dependency('fortran_stdlib')
