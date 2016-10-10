
## .drone.sec 

```
cat drone-secrets.yml

environment:
  # Your Docker account information to publish the container
  DOCKER_USERNAME: johnsmith
  DOCKER_PASSWORD: HowSecure1901
  DOCKER_EMAIL: john.smith@domain.intra
  SPARK_TOKEN: akssdfAFasdfkjaSDFAsdfkasfdaSDFasdf
  SPARK_ROOM: Y2lzYakssdfAFasdfkjaSDFAsdfkasfdaSDFasdf

drone secure --repo jsmith/app --in drone-secrets.yml

cat .drone.sec

RJdYPeEDRoKSBk5iW8BInMorBatA40I6ZfKqlPj4yWOHfRVdUntS0Uf6OhMszCyenHQEqntUAOeLYg.SegQH26g7wefYp9J.9ON1xGeH-KaVIzIYkgZLDwx0so_SrcKjWCbh3F5oeksNGIrZ2gcsFY3T79PF_SMhvX2OuRoz3S3rT6qKPiBf1PSr3ttlyITug4003QR3bDDK-7QaVJ-dmycV5tnd4dFSflRrmchlaNQ541-SX7Q9DFR1-meeVCMme9an57JtdrW2uLC4FvHRxmmeSIE

```

