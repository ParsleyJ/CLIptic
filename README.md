# CLIptic

Trigger MacBook haptic feedback from command line (for fource-touch enabled trackpads). Written in Swift.

### Usage

Launching the executable performs a single "medium" click. You can, however, customize this by adding arguments. For example, the following command performs a "vibration" feedback by executing 100 "strong" click feedbacks.

```bash
./CLIptic --type strong -n 100
```

The supported click types are: `backClick`, `click`, `weak`, `medium`, `weakMedium`, `strong`.

