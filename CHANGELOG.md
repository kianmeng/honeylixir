# 0.3.0

* **BREAKING**: Change LICENSE from MIT to Apache-2.0
* **BREAKING**: `Honeylixir.Transmission` no longer has a singular `send_event` for sending individually. If you want to explicitly send an event rather than queueing it up for background sending, please use `Honeylixir.Client.send_event/1` directly.
* Support queueing events and sending in batches
* Provide `Honeylixir.Response` for storing data about event send attempts and `Honeylixir.ResponseQueue` to pull them.

# 0.2.0

* Add fuller documentation
* Updated `service_name` not to be set to `nil` on the event if it isn't configured

# 0.1.0

* Support creating and sending basic events
