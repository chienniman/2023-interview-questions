## cron
`app/Console/Kernel.php`
清除數據

## Artisan Commands
`$schedule->command('emails:send Taylor --force')->daily();`

## Queued Jobs
`$schedule->job(new Heartbeat)->everyFiveMinutes();`

## Shell Commands
`$schedule->exec('node /home/forge/script.js')->daily();`