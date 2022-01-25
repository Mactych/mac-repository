# Corrupted Files
A list of corrupted files is listed below, I've added files here that I wasn't able to unarchive making me suspect that they are corrupted.
I tried multiple methods of unarchiving the packages ([pkgutil --expand-full](https://www.manpagez.com/man/1/pkgutil/), [pacifist](https://www.charlessoft.com), [suspicious package](https://mothersruin.com/software/SuspiciousPackage/)) and neither of them allowed me to extract a file.

The MD5 hash that corresponds with the listing for the corrupted file, is the MD5 hash of the package nested within the DMG.

- [ ] macOS 10.15.3 Intel Combo Upd.dmg
	- MD5: 695757ADF12B9B9A2FC1309B2376922A
	- (pkgutil --check-signature) package is invalid (checksum did not verify)
	
- [ ] macOS 10.15.4 Intel Combo Upd.dmg
	- MD5: 22DAF8AFD7D7D90CAA29AF27F79C2ED1
	- (pkgutil --check-signature) package is invalid (checksum did not verify)

- [ ] macOS 10.15.7 Intel Upd.dmg
	- MD5: 0319B0314AE54129F80187ACF0571AE6
