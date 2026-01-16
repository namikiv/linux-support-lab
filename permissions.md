# File Permissions and Ownership

## Viewing file permissions
```bash
ls -l
```

## Understanding permission structure
```text
-rwxr-xr--
│ │  │  └─ others permissions
│ │  └──── group permissions
│ └─────── owner permissions
└───────── file type
```

## Changing file permissions
```bash
chmod 644 file.txt
chmod 755 script.sh
```

## Changing file owner and group
```bash
sudo chown user file.txt
sudo chown user:group file.txt
```

## Permission denied troubleshooting
```bash
chmod +x script.sh
```

## Use case
User cannot execute a script due to missing execute permission.
Permissions were updated to resolve the issue.
