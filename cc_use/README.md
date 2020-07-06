# How to use on CC Systems

1. `module load scipy-stack/2019b`
2. `cd` to a directory with `*.pyx` files
3. Run `cythonize -i sieve_fast.pyx`
 * Additionally to use the `setup.py` file you may run `python setup.py build_ext --inplace`
4. You should now see several lines of GCC output, and newly created files
5. Open a Python interpreter to test via:
 * `import sieve_fast as sf`
 * `sf.sieve_table_fin(1_000)`
