# Start Postgres (bash)
### Go here
```bash
cd "/c/Program Files/PostgreSQL/16/bin"
```
### Run to start 
```bash
./pg_ctl start -D "/c/Program Files/PostgreSQL/16/data"
```

### Run to stop
```bash
./pg_ctl stop -D "/c/Program Files/PostgreSQL/16/data"
```
### Run to check status
```bash
./pg_ctl status -D "/c/Program Files/PostgreSQL/16/data"
```
# PowerShell Commands
### Check for processes using port :5432
```powershell
netstat -aon | findstr :5432
```
### Check for Postgres processes 
```powershell
tasklist | findstr postgres
```
# Check Logs 
### Navigate to logs
```bash
cd "/c/Program Files/PostgreSQL/16/data/log"
```
### List all logs 
```bash
ls -ltr
```
### Print log
```bash
cat <log-name>
```
