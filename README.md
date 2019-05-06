Seeed deb Package Repository for STM32MP1
==============================================

| Codename | Architecture | 
| :------: | :----------: |
| buster   | armhf        | 


### Add repository
```
# For STM32MP1
echo "deb https://seeed-studio.github.io/st_repo/ buster main" | sudo tee /etc/apt/sources.list.d/seeed.list
```

### Add public GPG key
```
curl https://seeed-studio.github.io/st_repo/public.key | sudo apt-key add -
```
