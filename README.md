# go-net-cli
This a simple cli in go built with urfave. This command line return many DNS information about a domain

### Commands

```bash
   ns       # Looks up the Name Servers for a particular Host
   ip       # Looks up the IP addresses for a particular host
   cname    # Looks up the CNAME for a particular host
   mx       # Looks up the MX records for a particular host
   help, h  # Shows a list of commands or help for one command
```

### Example 
```bash
  go run main.go ip --host youtube.com
```
