# StoreFront Studio — operating procedures

Use these procedures as task-oriented reference. They describe public capabilities and verification steps, not private implementation. UI labels can vary by version.

## Procedure 1: Verify a localized screenshot matrix

### Before you begin

Prepare source captures by device and locale; use sample accounts.

### Steps

1. List target locales, device slots and required image order.

2. Confirm each source capture is in the intended language and matches the staged device.

3. Inspect headlines for line breaks, clipping, right-to-left reading order and contrast.

4. Export and inspect full-resolution files, including the narrowest layout and longest text.

5. After upload, check the actual app/version/locale slots and image order in App Store Connect.

### Expected result

Every intended matrix cell contains the right images in the correct order.

### If the result differs

If a layout does not adapt cleanly, adjust that variant rather than accepting clipped text. Uploaded assets still require review; upload completion is not approval.

## Procedure 2: Update a screenshot after an app change

### Before you begin

Keep the previous approved set as a reference.

### Steps

1. Identify which feature and source screens changed.

2. Replace captures that no longer show the shipped behavior.

3. Review the headline against the new capture and remove outdated promises.

4. Recheck related localized variants and device layouts.

5. Export a clearly named revision and verify the destination before replacing assets.

### Expected result

The marketing image describes a visible feature in the current app.

### If the result differs

Do not fix an outdated interface with a headline alone. Preserve clean original captures for future revisions.

## Report a repeatable problem

Record app/version, device/OS, selected mode, input conditions and the smallest failing step. Distinguish expected behavior from the observed result. Use synthetic examples and omit credentials or private records.

[Documentation index](README.md) · [Capabilities and limits](FEATURES_AND_LIMITS.md) · [Support and sources](PRIVACY_AND_SUPPORT.md)
