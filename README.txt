ORIGINAL IMAGE VERIFICATION PACKAGE

Contains both creation-record PDFs and the four original PNG files, unchanged.
All four original PNG SHA-256 hashes were recalculated and match their corresponding PDF records.

The hashes in the PDFs describe the original PNG files, not images extracted from the PDFs. PDF embedding can change image encoding; an extracted image may have a different file hash despite showing the same pixels.

To verify on Windows PowerShell after extracting, run:
Get-FileHash -Algorithm SHA256 "path-to-original.png"
Compare with SHA256SUMS.txt or verification_manifest.json.

This is a local file-integrity check, not independent attestation of creation history, creation time, copyright ownership, name availability or legal clearance.
