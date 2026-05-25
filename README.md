The reliability of cyber forensic evidence acquisition is highly influenced by the underlying operating systems—Windows, Mac, and Linux—due to inherent variations in
file system structures, encryption protocols, and the compatibility of forensic tools.
Disk forensics, one of the most widely used techniques in digital investigations, faces
distinct obstacles on each platform. Windows, with its predominantly NTFS and
FAT file systems, typically supports reliable disk imaging and analysis through established tools such as FTK Imager and Autopsy/Sleuthkit. However, encryption
features frequently pose challenges to evidence acquisition. Conversely, Linux environments, which rely on file systems like ext4 and XFS, generally offer greater transparency; yet, the transient nature of log retention often complicates forensic analysis
efforts. In instances where anti-forensic strategies such as encryption and compression
render traditional disk forensics insufficient, memory forensics emerges as an essential approach. While memory forensic methodologies demonstrate robustness across Windows and Linux platforms through frameworks like Volatility, platform-specific
difficulties persist. Memory analysis on Linux systems benefit from tools like LiME,
snapshot utilities, and dd for memory acquisition. Nevertheless, data volatility during
live memory acquisition on Linux can still present challenges. The research here seeks
to systematically assess both disk and memory forensic acquisition techniques across
varied samples representing Windows and Linux systems. By identifying the most
effective combinations of forensic tools and configurations tailored to each operating
system, the study aims to improve the accuracy and reliability of evidence collection.
Furthermore, it critically evaluates the capabilities of current forensic tools, exposing a
persistent research gap: the consistent assurance of forensic input reliability and footprint integrity. Through the integration of static analysis and temporal performance
evaluations, this study emphasizes the importance of developing standardized forensic
procedures and practices to ensure the integrity and admissibility of evidence across
diverse platforms. The establishment of such standardised methodologies is imperative
to maintaining the credibility and reliability of cyber forensic investigations in heterogeneous operating system environments.
