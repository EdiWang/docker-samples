# Docker Samples

Sample Dockerfile for build apps

## Examples

Combination | Example Directory | Build | Run
--|--|--|--
Angular + Nginx | `./angular-nginx` | `docker build . -t example-angular-nginx` | `docker run -d -p 80:80 example-angular-nginx`
React + Nginx | `./react-nginx` | `docker build . -t example-react-nginx` | `docker run -d -p 80:80 example-react-nginx`
Pure HTML + Nginx | `./static-html-nginx` | `docker build . -t example-static-html-nginx` | `docker run -d -p 80:80 example-static-html-nginx`
Pure HTML + SWS | `./static-html-sws` | `docker build . -t example-static-html-sws` | `docker run -d -p 8080:8080 example-static-html-sws`
Blazor WASM + Nginx | `./blazor-wasm-nginx` | `docker build . -t example-blazor-wasm-nginx` | `docker run -d -p 80:80 example-blazor-wasm-nginx`
