# WHMCS Gravatar
Simple WHMCS hook for displaying gravatar profile pictures

## Usage
### 1. Place file in hooks folder

```shell
cd /your/whmcs/installation/includes/hooks
git clone https://gitlab.com/PhaseHosting/whmcs-gravatar.git gravatar && mv gravatar/gravatar.php ../hooks && rmdir gravatar
```

Or

Just download the file and put it in the hooks folder

### 2. Update WHMCS template
To display the users profile picture, simply use this code where you want to 
display it.

```html
<img src="{gravatar email=$clientsdetails.email rating="PG" size="60" }" alt="user image">
```



