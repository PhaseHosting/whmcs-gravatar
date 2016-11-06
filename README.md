# WHMCS Gravatar

## Usage
### 1. Place file in hooks folder

```shell
cd /your/whmcs/installation/includes/hooks
git clone ... gravatar && mv gravatar/... ../hooks && rmdir gravatar
```

### 2. Update WHMCS template
To display the users profile picture, simply use this code where you want to 
display it.

```html
<img src="{gravatar email=$clientsdetails.email rating="PG" size="60" }" alt="user image">
```



