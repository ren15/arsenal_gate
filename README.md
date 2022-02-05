# arsenal_gate

For a high-performance live data science stack, we need the following

### shared_memory ipc
servo: Shm

boost: https://theboostcpplibraries.com/boost.interprocess-managed-shared-memory

### message_queue

folly: MPMCQueue, ProducerConsumerQueue, UnboundedQueue

### expression lazy evaluation

range-v3, expression template

Details: https://github.com/ren15/lazy_dag

### data storage / database
clickhouse, databend, polars

### FFI

Rust/C++ FFI, with performance in mind.

servo from firefox

https://github.com/ren15/rust_cpp_bench  
https://github.com/ren15/rust_to_so  
https://github.com/ren15/rust_call_cpp   
https://github.com/ren15/xlanglto  


### Compiler Optimization

https://github.com/ren15/cc_on_distros  
https://github.com/ren15/cc_compare  

### Intel toolchains

https://github.com/ren15/devcloud_cookbook  

### Github infra

https://github.com/ren15/runner_grid  
https://github.com/ren15/ci_29193608  


