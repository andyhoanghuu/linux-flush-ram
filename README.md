# Clear RAM Memory Cache, Buffer and Swap Space on Linux

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Excute](#markdown-header-installation)

## Main Functionalities
Like any other operating system, GNU/Linux has implemented a memory management efficiently and even more than that. But if any process is eating away your memory and you want to clear it, Linux provides a way to flush or clear ram cache.
## Excute
### Cron

- `sudo nano -w flushram.sh`
- `chmod 755 flushram.sh`
- `crontab -e`
 press: 1
- `0  2  *  *  * /home/flushram.sh`

For example, append the below line, save and exit to run it at 2am daily.

### Manual
`sudo sh flushram.sh`
