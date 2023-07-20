## Sending
* `use Notifiable`
* `$user->notify(new InvoicePaid($invoice));`
* `Notification::send($users, new InvoicePaid($invoice));`

## type
* Slack
* mail
* SMS
