# vuln-go-2
Simple golang script with xss vulnerability
Edit main.go and add this code snippet on line 42. Create a PR. Wait for validation.

```go
fmt.Fprintf(w, str)
```
