# Build Your Own Route Test Script
## Set Up

### Start pox
```bash
/opt/pox/pox.py −−verbose ucla_cs118
```
### Start router
```bash
make
./router
```

### Start test script
```bash
sudo ./test.py
```

# FAQ
- Exception: Error creating interface pair (server1-eth0,sw0-eth1): RTNETLINK answers: File exists
    ```bash
    sudo mn -c
    ```

