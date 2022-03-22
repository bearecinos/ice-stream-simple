# ice-stream-simple

Steps:

1. Clone the `ice-stream-simple` repository
2. Clone my version of [fenics_ice (branch taylor_test)](https://github.com/bearecinos/fenics_ice/tree/taylor_test)
3. Switch to the fenics_ice version that has the taylor tests:
   `git checkout taylor_test`
4. Activate fenics_ice conda environment.
5. On the command line do: 

```
export RUN_DIR=$FENICS_ICE_BASE_DIR/runs/
cd ice-stream-simple
python $RUN_DIR/run_taylor_inv.py ice_stream.toml
python $RUN_DIR/run_taylor_fwd_inv.py ice_stream.toml

```


