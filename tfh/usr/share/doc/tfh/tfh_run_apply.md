## `tfh run apply`

Confirm and apply a run that needs confirmation.

### Synopsis

    tfh run apply [RUNID] [-comment COMMENT]

### Description

Confirms a run that needs confirmation to be applied.

### Positional parameters

* `RUNID`

ID of the run to be confirmed. If omitted, the lastest run with `is-confirmable` action available is confirmed.

### Options

* `-m, -message, -comment COMMENT`

An optional explanation for why the run was confirmed.
