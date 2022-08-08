cargo build
cargo run the poem.txt  
// here 'the' is the 1st argument(query to be searched in the file poem.txt) and 'poem.txt' is the filename


Note: By default querying is case sensitive
Hence: cargo run and poem.txt => No result

After using `export CASE_INSENSITIVE=true`
Hence: cargo run and poem.txt => Results in 2 lines

`unset CASE_INSENSITIVE`
takes CLI to default state


` cargo run and poem.txt > output.txt`  //to store output in a file
