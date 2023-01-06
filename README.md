You can run the tests using the following command:

$ go test
If everything passed, tidy up a bit by running:

$ go mod tidy
Then run the tests again, just to be sure:

$ go test
For more verbose output try this:

$ go test -v
Sometimes test results are cached. To make sure they are not, use this command:

$ go test -count 1
$ go test -v -count 1
For more information on testing, run this command:

$ go help testflag



echo "# go-lib" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Tanzin-Ul-Islam/go-lib.git
git push -u origin main