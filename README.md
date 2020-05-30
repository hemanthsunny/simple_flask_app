#Useful commands:
1. gcloud builds submit --tag gcr.io/[project-id]/<container-name>
2. gcloud run deploy --image gcr.io/[project-id]/flask-fire

#For this project:
3. gcloud builds submit --tag gcr.io/simple-flask-app-f86b5/flask-fire
4. gcloud run deploy --image gcr.io/simple-flask-app-f86b5/flask-fire

<!-- For frontend deploy -->
5. firebase init hosting
6. firebase deploy

#To update gcloud
7. gcloud components update
 
#References:
1. Blog: https://medium.com/firebase-developers/hosting-flask-servers-on-firebase-from-scratch-c97cfb204579
2. Video: https://youtu.be/t5EfITuFD9w
