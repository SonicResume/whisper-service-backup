# Whisper Transcription Service

A hosted Whisper-powered transcription service that applications can use
when speech-to-text is required.

## What It Does

The service accepts supported audio and video recordings and converts
spoken content into text using Whisper.

It is designed to be used by applications, tools, and temporary workflows
that need transcription without having to operate their own transcription
engine.

## Service Use

Applications can use the service when transcription is needed for a
particular task or workflow.

Examples include:

- Interview transcription
- Audio and video transcription
- Recorded conversations
- Intake workflows
- Scheduling and booking workflows
- Temporary application tools
- Other authorized workflows requiring speech-to-text

A workflow can use the transcription capability temporarily and stop using
it when the task is complete.

## How It Works

An authorized application submits an audio or video recording.

The service processes the media with Whisper and returns the resulting
transcription to the requesting application.

The underlying Whisper processing infrastructure is privately operated.

## Access

The service is intended for authorized application use.

Access control is required before a request can be processed.

The service's connection details and authentication credentials are
intentionally kept outside this repository.

## Privacy

Recordings and transcripts may contain confidential information.

Applications using the service are responsible for handling submitted media
and returned transcripts appropriately.

Temporary processing data should be removed when it is no longer required.

## Integration

The service is designed to be reusable.

An application can integrate the transcription capability when needed
without embedding a separate transcription engine into the application.

## Repository

This repository contains the service documentation and source required to
maintain and recover the service.

Private infrastructure details, connection information, credentials,
certificates, model files, recordings, and confidential transcripts are not
stored here.
