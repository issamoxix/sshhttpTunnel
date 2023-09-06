# SshHttpTunnel
 this code sets up both an SSH server and an HTTP server. Clients can establish SSH connections to the server and create named tunnels for data transfer over SSH. The HTTP server allows clients to request access to specific tunnels by providing an "id" in the URL query. The tunnels are managed using goroutines and channels, ensuring concurrent access and proper handling of data transfer.

## Source
Tutorial from : <br>
https://www.youtube.com/watch?v=RK5xh7xH1Jw