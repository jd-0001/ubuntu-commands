# ubuntu-commands
List of useful ubuntu commands

## Services

**List all services:** `service --status-all`
  
**Start Service:** `sudo service <service-name> start`
  
**Service Status:**
  
[ + ] <= running
  
[ - ] <= Stopped
  
[ ? ] <= without a 'status' command

## File Management

**Remove only directory within folder:** `rm -r */`
  
**Find and Remove File:** `find . -type f -name "BuyNow.vue" -exec rm {} \;` - [Full Guide](https://www.cyberciti.biz/faq/linux-unix-how-to-find-and-remove-files/)
  
**Move multiple files:** `mv file_name file_name folder_name`
```bash
# mv <file> <file> ... <folder_name>
mv config.py main.py other.py backup
```
