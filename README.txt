first commit --> before Tar --> file (go.txt, js.txt, rust.txt)
go.txt --> 37B
js.txt --> 28B
rust.txt --> 30B

second commit --> after Tar --> same size (tar -cfv app.tar ./app/)
go.txt --> 37B
js.txt --> 28B
rust.txt --> 30B
total --> 13K

third commit --> after app.Tar --> re size (tar -czvf app.tar.gz ./app/)
go.txt --> 37B
js.txt --> 28B
rust.txt --> 30B 
total --> 659B