# Setup


# Prove
~~~
zkwasm-cli --params ./params testwasm prove --output ./output --wasm ./output.wasm  --public 3:i64,2:i64
~~~

# Verify
~~~
zkwasm-cli --params ./params testwasm verify --output ./output 
~~~