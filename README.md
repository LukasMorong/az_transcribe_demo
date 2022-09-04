# AMAZON Transcribe DEMO

## INSTALL

```
pip install -r requirements
```

## RUN

```
python app.py
```

https://pypi.org/project/amazon-transcribe

## SETUP AWS

1. create AWS account (credit card required)
2. install aws-cli
3. configure credentials

```
aws configure
```

Create acess key

https://console.aws.amazon.com/iam/home?#security_credential

Available zones (eu-central-1)
https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.RegionsAndAvailabilityZones.html

eu-central-1

https://docs.aws.amazon.com/transcribe/latest/dg/getting-started-console.html

Limitations
60hours

Audio formats supported for streaming transcriptions are:

    FLAC

    OPUS-encoded audio in an Ogg container

    PCM (only signed 16-bit little-endian audio formats, which does not include WAV)

Language can be chosen or detected automatically

- Czech not included

provides speaker identification
