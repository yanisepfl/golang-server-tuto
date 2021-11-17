# GOLANG SERVER

## INTRO

As a true Blockchain enthusiast, I had to learn Solidity and Golang to participate to several projects. This repository consists of a very simple Golang server handling basic GET and POST requests. 

## USAGE

1. Run the server : `go run server.go`
2. Going to `http://localhost:8080/` should lead you to `index.html`
3. Going to `http://localhost:8080/hello` should display "Hello!"
- Try `curl -X POST http://localhost:8080/hello` & `curl -X POST http://localhost:8080/hell` to see the two error paths
4. Going to `http://localhost:8080/form.html` should lead you to `form.html`
- Complete the form and then submit, it should lead to `http://localhost:8080/form` with the correct successful message.
5. Going to `http://localhost:8080/sortArrayForm.html` should lead you to `sortArrayForm.html`
- Completing the form with coma separated numbers output a sorted array.