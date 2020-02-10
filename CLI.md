# CLI cheat sheet

https://cloud.google.com/sdk/gcloud/reference

## Config

    gcloud config list

Set the default zone:

    gcloud config set compute/zone australia-southeast1-b

## Zones and regions

    gcloud compute regions list

    gcloud compute zones list

Just list the info for the AU region

    gcloud compute zones list --filter "region:australia"
