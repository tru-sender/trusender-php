TruSender PHP client is using cURL on top on our Rest API. Here's how to use it:

```php
require_once('PATH/TO/FILE/trusender.php');

$ts = new TruSender("YOUR_AUTH_TOKEN");

$ts->send_email("template_name", "to_address", $data_mapping);
$ts->send_event("event_name", "to_address", $event_properties);

```

