---
layout: page
title: Privacy Policy
permalink: /privacy/
include_in_header: false
description: BeforeShare explains how photos, face detection results, text recognition, codes, and metadata are processed on-device and how long they are retained.
page_eyebrow: Legal
page_highlights:
  - On-device processing
  - No photo uploads
  - Face data stays in memory
keywords: BeforeShare privacy policy, face detection data, on-device photo privacy, blur faces iphone privacy
---

<div class="legalBanner">
  <p class="legalLead">BeforeShare is built to help people review photos for privacy leaks before sharing them. This policy explains what BeforeShare processes on-device, what never leaves your phone, and how face detection data is handled.</p>
  <div class="legalMeta">
    <div class="legalMetaItem">
      <span>Effective date</span>
      <strong>March 23, 2026</strong>
    </div>
    <div class="legalMetaItem">
      <span>Applies to</span>
      <strong>BeforeShare for iPhone</strong>
    </div>
    <div class="legalMetaItem">
      <span>Contact</span>
      <strong><a href="mailto:x5brain@gmail.com">x5brain@gmail.com</a></strong>
    </div>
  </div>
</div>

<nav class="legalNav" aria-label="Privacy Policy sections">
  <a href="#introduction">Introduction</a>
  <a href="#information-we-collect">Information We Collect</a>
  <a href="#face-detection-data">Face Detection Data</a>
  <a href="#how-we-use-your-information">How We Use Information</a>
  <a href="#information-sharing-and-disclosure">Sharing and Disclosure</a>
  <a href="#data-storage-and-security">Storage and Security</a>
  <a href="#data-retention-and-deletion">Retention and Deletion</a>
  <a href="#your-rights">Your Rights</a>
  <a href="#childrens-privacy">Children's Privacy</a>
  <a href="#contact-us">Contact</a>
</nav>

## Introduction {#introduction}

BeforeShare is a photo privacy app for iPhone operated by the app developer, who can be reached at [x5brain@gmail.com](mailto:x5brain@gmail.com). This Privacy Policy applies to the BeforeShare iOS application, the website at [https://youllbe.cn/beforeshare.app/](https://youllbe.cn/beforeshare.app/), and support communications related to the app.

BeforeShare is designed so that core scanning and redaction features run locally on your device. In normal use, your selected photos do not leave your iPhone for analysis.

## Information We Collect {#information-we-collect}

<div class="legalGrid">
  <div class="legalCard">
    <p class="legalCardLabel">Photos you choose</p>
    <p>User-selected photos are scanned locally on your device so you can review privacy risks before sharing. BeforeShare does not upload those photos to our servers for processing.</p>
  </div>
  <div class="legalCard">
    <p class="legalCardLabel">Text recognition data</p>
    <p>OCR results used to identify visible text are generated on-device during a scan session and discarded after the session ends.</p>
  </div>
  <div class="legalCard">
    <p class="legalCardLabel">Barcode and QR code data</p>
    <p>Barcode and QR detection results are processed on-device so you can review them before export. They are not shared with third parties and are discarded after the active session.</p>
  </div>
  <div class="legalCard">
    <p class="legalCardLabel">EXIF metadata</p>
    <p>BeforeShare can read photo metadata such as location, timestamps, and device information on-device so you can review or remove it before export.</p>
  </div>
  <div class="legalCard">
    <p class="legalCardLabel">Analytics and diagnostics</p>
    <p>BeforeShare does not currently use third-party advertising SDKs or cloud AI services, and it does not currently collect product interaction analytics as part of the core workflow.</p>
  </div>
  <div class="legalCard">
    <p class="legalCardLabel">Support emails</p>
    <p>If you contact us, we receive the information you include in your email so we can respond to your request.</p>
  </div>
</div>

## Face Detection Data {#face-detection-data}

<div class="legalNote">
  <p><strong>What we collect:</strong> BeforeShare uses Apple's on-device Vision framework (<code>VNDetectFaceRectanglesRequest</code>) to detect face positions in user-selected photos. We only obtain bounding box coordinates (rectangular positions) and confidence scores. We do <strong>not</strong> collect facial features, facial geometry, face embeddings, faceprints, or any form of biometric identifier.</p>
  <p><strong>How we use it:</strong> Face position data is used solely to highlight detected face regions in the app's scanning interface, allowing users to review and apply blur or redaction to faces before sharing photos. This is a privacy-protection feature designed to help users safeguard the identity of individuals in their photos.</p>
  <p><strong>Third-party sharing:</strong> Face detection data is never shared with any third party, including analytics providers, advertisers, or cloud services.</p>
  <p><strong>Storage:</strong> Face detection data is processed entirely on-device using Apple's Vision framework. It exists only in volatile memory (RAM) and is never written to disk, never cached, and never backed up to iCloud or any external storage.</p>
  <p><strong>Retention:</strong> Face detection data is retained only for the duration of the active scan session. It is immediately and permanently discarded when the user navigates away from the scan results or closes the app.</p>
</div>

BeforeShare uses face detection strictly as a privacy-protection tool. It is not designed or used for identity recognition, profiling, advertising, or biometric analysis.

## How We Use Your Information {#how-we-use-your-information}

We use locally processed information only to:

- scan photos for privacy risks before sharing
- highlight faces, text, QR codes, barcodes, and other sensitive details in the app
- generate a safer export by blurring, redacting, or removing metadata from the user-selected image
- respond to support requests you send us by email

If anonymous product analytics are introduced in the future, they will be described here before collection begins.

## Information Sharing and Disclosure {#information-sharing-and-disclosure}

- We do not sell user photos, face detection data, or personal information.
- We do not share user photos, OCR results, barcode or QR results, or face detection data with advertisers, analytics providers, or cloud AI services.
- We do not send selected photos to third-party AI models or remote image processing services as part of the core BeforeShare workflow.
- If you email support, your message may be processed by standard email providers solely so we can receive and reply to it.

## Data Storage and Security {#data-storage-and-security}

- Photo processing takes place entirely on the user's device.
- Face, text, barcode, and QR detection results are intended to remain in memory only for the active session.
- Exported photos are saved to the user's photo library or shared destinations only when the user chooses to export or share them.
- Temporary previews or cache files, if any are created to support active editing, remain on-device only and are not transmitted to us.
- We use reasonable measures appropriate to an on-device workflow to avoid unnecessary retention or transmission of scan data.

## Data Retention and Deletion {#data-retention-and-deletion}

- Active scan data is discarded when the scan session ends, when the user leaves the scan results, or when the app is closed.
- Support emails may be retained only as long as needed to respond, maintain records of the request, or comply with legal obligations.
- If local cache exists on the device, users can remove it through available in-app cache controls or by deleting the app.
- Users can withdraw future access to photos or other device permissions at any time through iOS Settings.
- If you want us to delete support correspondence or other information we hold directly, email [x5brain@gmail.com](mailto:x5brain@gmail.com).

## Your Rights {#your-rights}

Depending on your location and the limited information we may hold, you may have the right to:

- request access to the personal information you provided directly to us
- request correction or deletion of that information
- withdraw consent for permissions you granted on your device
- contact us with privacy questions or deletion requests

Because BeforeShare is designed to process photos locally, we often do not possess the photo, face, OCR, barcode, QR, or EXIF data generated during your scan session.

## Children's Privacy {#childrens-privacy}

BeforeShare is not directed to children under 13, and we do not knowingly collect personal information from children under 13. If you believe a child has provided personal information to us directly, please contact us so we can delete it.

## Changes to This Privacy Policy {#changes-to-this-privacy-policy}

We may update this Privacy Policy from time to time. If we make a material change, we will post the updated version on this page and update the effective date above. Where required, we will provide additional notice inside the app or through the App Store listing.

## Contact Us {#contact-us}

For privacy questions, deletion requests, or general support, contact [x5brain@gmail.com](mailto:x5brain@gmail.com).

## Effective Date {#effective-date}

This Privacy Policy is effective as of **March 23, 2026**.
