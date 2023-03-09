### Podcastwala
Your very own Podcast web app built with Laravel 5. This web app enables you to manage RSS feeds for your favorite podcasts and listen to the episodes in a seamless UI. New episodes published by podcasts are automatically updated on a daily basis. Mark the items you have listened to as read and much more. 


### Features
 * Manage RSS feeds for your favorite podcasts
 * New episodes published by podcasts are updated automatically
 * Mark episodes you have listened to as read
 * Search for episodes by title and description
 * Mark all previous episodes in a podcast as read
 * Mark your favorite episodes, accessible via the ```podcast/favorites``` link

 Note: manually update new episodes by navigating to route ```podcast/auto-update```

### Install Instructions
To install Podcastwala you can clone the repository:

```
$ git clone git@github.com:shivani446/podcast-kubernetes.git
```

then to run command

```
kubectl apply -f k8s
```
and then go to file named hoats 

```
sudo vim /etc/hosts
```
now edit it by adding 
```
10.0.17.106 shivani.local
```
now open browser and search 
```
shivani.local/
```
FINALLY you can see the PODCAST app


