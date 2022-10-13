### Reveal

Pre-reveal, we need to :

* Hash metadata
	```bash
	./hash_metadata.sh
	# ac117b49e157666092c5f5caa237a9049cc18ae3
	```

* Compute a hash of the shuffle algorithm, containing the seeded random shuffle and metadata hash.
	```bash
	./hash_shuffle.sh
	# 48b220ad931777a0b2a11f3a6d65bc5d1df6139fe9e137116e8a5b8d67b86941
	```

This final hash is committed on-chain before the reveal() call
