# NGINX Learning Roadmap

A hands-on guide to learning NGINX fundamentals. This roadmap helps you build a strong foundation before diving into system design, cloud, and Kubernetes.

---

## 🧠 NGINX Architecture

- **Deploy NGINX**  
  Install NGINX and start the service.

- **Run NGINX in foreground vs background**  
  Learn the difference between daemonized and foreground mode.

- **Run NGINX as non-root**  
  Understand user permissions and improve security.

- **Understand master vs worker process usage**  
  Learn how NGINX uses master and worker processes for performance.

- **CPU/Memory consumed**  
  Monitor resource usage using tools like `top`, `htop`, or `ps aux`.

- **How files are managed**  
  Explore NGINX’s directory structure: configs, logs, web root.

- **How privileged ports are assigned**  
  Understand how NGINX binds to ports below 1024 and drops root privileges.

- **Understand port binding**  
  Learn how services bind to specific ports.

- **Bind to specific IP or interface**  
  Control which IP addresses NGINX listens on.

- **File permissions set by NGINX**  
  Check ownership and permissions of NGINX-related files and folders.

- **Key config files**  
  Work with `nginx.conf`, `sites-available/`, and `sites-enabled/`.

- **Reload vs Restart**  
  Understand signal handling like `SIGHUP`, `SIGTERM`, and how graceful reload works.

- **Limit access by IP / method**  
  Use config to restrict access based on IP or HTTP methods.

---

## 🌐 Serving Websites

- **Serve static files from a custom location**  
  Host HTML, CSS, JS, or image files using NGINX.

---

## 📜 Logging

- **Check logs and understand its format**  
  Explore `access.log` and `error.log`. Learn how to read log fields.

---

## 🌍 DNS and Domain Concepts

- **Virtual hosts concept**  
  Use server blocks to host multiple websites on a single server.

- **Map the server to a domain name**  
  Use `/etc/hosts` for local mapping or set up DNS A records.

- **Learn subdomain concepts**  
  Serve `sub.domain.com` from separate config or web root.

---

## 🔁 Reverse Proxy and Load Balancing

- **Reverse proxy setup**  
  Forward requests to a backend service like Node.js, Python, or Go.

- **Upstream and load balancing**  
  Load balance requests across multiple backend servers using round-robin or failover.

- **Health checks**  
  Configure passive health checks to manage upstream availability.

---

## 🔀 URL Rewriting and Routing

- **URL rewriting with regex**  
  Use `rewrite` and `location` blocks with regular expressions to redirect or modify URLs.

- **Redirect HTTP to HTTPS**  
  Force HTTPS redirection with a simple rule.

- **Custom 404 pages**  
  Show friendly error pages for invalid routes.

---

## 🔒 SSL and Security

- **Enable HTTPS with self-signed cert**  
  Practice setting up SSL manually.

- **Use Let's Encrypt for free SSL**  
  Automate certificate provisioning using `certbot`.

- **Add security headers**  
  Improve browser security by adding headers like `X-Frame-Options`, `X-Content-Type-Options`, and `Content-Security-Policy`.

- **Rate limiting and request throttling**  
  Protect your server with rules like `limit_req` and `limit_conn`.

- **Basic authentication**  
  Add simple username/password protection using `.htpasswd` and `auth_basic`.

---

## 🧩 Modular Configuration

- **Include reusable config snippets**  
  Break down configs using `include` for cleaner management.

---

## 🛠 Debugging and Tools

- **Test config without restarting**  
  Use `nginx -t` to validate syntax.

- **Live tail logs**  
  Use `tail -f /var/log/nginx/access.log` to see real-time requests.

- **Check open ports and sockets**  
  Use `netstat -tulpn` or `ss -tuln` to list listening services.

---

## ✅ Final Tip

Use each section as a hands-on task. Practice each config on a test server or VM. Once you're confident with these topics, you’ll have a strong base to move into Docker and Kubernetes with clarity and confidence.
