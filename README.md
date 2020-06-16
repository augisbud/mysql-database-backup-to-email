# mysql-database-backup-to-email
simple php script to backup your mysql database save it locally and send it to any specified email
# requirements
phpmailer - https://github.com/PHPMailer/PHPMailer 
  you could use php's mail() function, however I already use this in my project and it's much simpler.
# recomendations
run it as a cron job every day or every other day
  0 0 * * * - every day at 00:00
# disclaimer
I haven't developed the function 'EXPORT_DATABASE' this has been pieced together from a few pieces of code I found on the internet.
