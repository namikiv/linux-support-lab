# User and Group Management

## Creating a user
```bash
sudo useradd support_user
sudo passwd support_user
```

## Adding user to a group
```bash
sudo usermod -aG sudo support_user
```

## Checking user groups
```bash
groups support_user
```

## Locking and unlocking a user
```bash
sudo usermod -L support_user
sudo usermod -U support_user
```

## Removing a user
```bash
sudo userdel support_user
```

## Use case
User requires temporary admin access to perform maintenance tasks.
