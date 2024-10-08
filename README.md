


# Go Web Server

A simple web server built with Golang that serves static files, handles form submissions, and responds to GET and POST requests.

## Features
- Serves static files (HTML).
- Handles POST form submissions.
- Responds to GET requests.

## Project Structure

go-server/
│
├── static/
│   ├── index.html   # Static page
│   └── form.html    # Form for user input
├── main.go          # Go web server code
```

## Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/go-web-server.git
   cd go-server
   ```

2. **Run the server**:
   ```bash
   go run main.go
   ```

3. **Access the server**:
   - Visit `http://localhost:8080/` to see `index.html`.
   - Visit `http://localhost:8080/form.html` to submit the form.

## Key Routes
- **`/`**: Serves static files from the `static/` directory.
- **`/form`**: Handles form submissions via POST.
- **`/hello`**: Responds to GET requests with a "hello" message.

## Additional Ideas
- Add form validation.
- Implement logging.
- Connect to a database to store form submissions.

## License
This project is licensed under the MIT License.
```
