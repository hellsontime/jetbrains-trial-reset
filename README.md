# The script resets JetBrains products trial period but keeps settings, logs and cache

Supports: Intellij IDEA, WebStorm, DataGrip, PhpStorm, CLion, PyCharm, RubyMine, GoLand and Rider

Please use it in study purpose only

## Usage
### Manually

- Close all JetBrains applications

- For first time only:
```shell script
chmod +x runme.sh
```
- Run script:
```shell script
./runme.sh
```
- Reboot

Every first day of each month the job will:
- Close all Intellij applications
- Reset evaluation
- Flush preference cache