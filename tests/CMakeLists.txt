add_executable(tests test_main.c ../src/csv.c)
add_test(NAME run_tests COMMAND tests)
