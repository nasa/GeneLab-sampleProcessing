 <img src="NASA_GeneLab_logo-2019.png" align="middle" alt=""/>

# GeneLab-sampleProcessing

### About
The NASA GeneLab Sample Processing Laboratory generates open science data from spaceflight missions. Over the years, it has developed a set of standard operating procedures (SOPs) that it utilizes to generate high-quality standardized data. This repository houses these SOPs.


## Tissue Storage and Cutting ##
#### [1.1 Sample aliquoting, labeling and storage](GeneLab-sampleProcessing/SOP_text/1.1_sample_archiving_v1.0.md) ####
This SOP describes in detail how GeneLab SPL handles sample storage, aliquoting, labeling and the consensus acronyms we use.

1.2 Frozen tissue cutting
This SOP describes the steps required to safely section a tissue prior the extraction of nucleic acids. The procedure, if followed correctly will allow portioning a piece of tissue without thawing and compromising the original biological sample.

Homogenization
2.1 Tissue homogenization using Bullet Blender Gold Bead Beater
This SOP describes the steps required to lyse and homogenize biological material using a Bullet Blender 24 Gold bead beater. This procedure was validated for downstream RNA/DNA extraction using the Qiagen AllPrep kits (SOP#3.1), it is also possible to use the procedure with downstream RNA extraction using Trizol (SOP#3.2).

2.2 Tissue homogenization using Polytron Rotor Stator Homogenizer
This SOP describes the steps required to homogenize biological samples using the handheld rotor stator homogenizer Polytron. This type of homogenator allow for a larger lysis buffer volume and is used mainly for samples that require larger yield and/or not yet optimized for bead homogenization. This procedure is currently routinely used for mouse skin RNA extraction that requires a downstream Trizol extraction (SOP#3.2).

Extraction
3.1 QIAGEN AllPrep DNA/RNA Mini (Cat#80204) with QIAGEN RNase-Free DNase Set. (Cat#79254)
This SOP describes the steps required to extract both RNA and DNA from mammalian tissues. The extraction kit used in this procedure is Qiagen AllPrep DNA/RNA Mini. In addition, in this procedure we describe steps for depleting the isolated RNA from DNA using QIAgen RNase-Free DNase set. This step is required for RNA that will be used for sequencing. It is strongly advised to read the AllPrep DNA/RNA Mini-Handbook in full.

3.2 TRIzol RNA Extraction with QIAGEN RNase-Free DNase Set and QIAGEN Allprep
This SOP describes the steps required to extract RNA from mammalian tissue using the TRIzol reagent for isolation and Qiagen Allprep mini kit for clean-up. In addition, in this procedure we describe steps for depleting the isolated RNA from DNA using QIAgen RNase-Free DNase set. This step is required for RNA that will be used for sequencing. It is strongly advised to read the AllPrep DNA/RNA Mini-Handbook in full.

3.3 Feces DNA Extraction using Maxwell RSC instrument with Purefood GMO kit
This SOP describes the steps required to isolate DNA from mouse fecal pellets using Maxwell RSC instrument with Purefood GMO kit.

DNA/RNA QC and Troubleshooting
4.1 RNA/DNA/miRNA/cDNA quantification using Qubit Fluorimeter
This SOP describes the steps required to perform quantification of RNA/DNA or cDNA using the Invitrogen (Thermo Fisher Scientific) fluorimeter – Qubit and the Qubit kits. Flourimetric methods are advantageous over spectrophotometric methods since they are more precise and specific to the molecule being measured.

4.2 QC genomic DNA
This SOP describes the steps required to perform automated electrophoresis of genomic DNA to assess DNA quality using the Agilent 4200 TapeStation System and Agilent Genomic DNA TapeStation reagents. Any number of samples can be analyzed between 1 and 96.

4.3 Quality analysis of RNA using Agilent Bioanalyzer 2100 System
This SOP describes the steps required to perform automated electrophoresis of RNA samples. This procedure is using the Agilent 2100 Bioanalyzer System and Agilent RNA 6000 Nano and Pico kits. This procedure will generate a gel image of the RNA as well as RIN and DV200 values, those are recorded and used to track sample quality.

Library Preparation
5.1 Illumina TruSeq Stranded Total RNA Library Prep using EpMotion
This SOP describes the steps used to automate library preparation using the Illumina TruSeq Stranded Total RNA Gold kit on an EpMotion 5073/5075.

5.2 Use of ERCC spike in mixes and UMRR/UHRR controls for Total RNA-Sequencing
As described in detail on GeneLab.nasa.gov webpage titled “GeneLab Sequencing Standards and Services” we encourage the researchers to use two levels of control in the Total RNA sequencing workflow. This SOP describes the suggested protocol.

5.3 Illumina Nextera DNA Flex Manual Library Preparation
This SOP follows the Illumina Nextera DNA Flex Library Prep Guide, Doc# 1000000025416 v07. It is strongly advised to read the guide in full before using this SOP.

Library QC and Troubleshooting
6.1 qPCR quantification of Illumina sequencing libraries
This SOP describes the steps for qPCR quantification of Illumina Sequencing libraries using a QIAgility.

6.2 Quant-iT PicoGreen dsDNA quantification of Illumina sequencing libraries
This SOP lists the steps for dsDNA quantification of sequencing libraries using the Quant-iT™ PicoGreen™ dsDNA Assay Kit.

6.3 QC cDNA
This SOP lists the steps for DNA quantification of sequencing libraries using an Agilent D1000 TapeStation.

6.4 Normalizing TruSeq Stranded Total RNA Library
This SOP describes the steps to normalize TruSeq Stranded Total RNA libraries.

6.5 TruSeq Total RNA library pooling, normalization and QC
This SOP describes the steps to pool, normalize, and check the quality of TruSeq Total RNA libraries using an Agilent Tapestation and an Illumina iSeq.

6.6 Manual Illumina TruSeq total RNA (Ribo Gold) library clean-up from adapter dimers
This SOP describes the steps for manually cleaning Illumina TruSeq Total RNA libraries of adapter dimers.

Sequencing Parameters
7.1 Setting up NovaSeq 6000 and iSeq 100 sequencers
This SOP describes the setup of Illumina NovaSeq 6000 and iSeq 100 sequences used by NASA GeneLab.

Sequencing QC and Troubleshooting
8.1 GeneLab SOP for Generating iSeq QC complete report from HTStream on MMOC
This SOP describes the steps for generating an iSeq quality control report using the high throughput genomic data pre-processing tool HTStream.

8.2 GeneLab SOP for Generating iSeq HTStream output to calculate library pooling values
This SOP describes the steps required to calculate library pooling volumes after the first iSeq (pool by volume) run and instructions on how to pool libraries when there is not enough volume.

If you have any questions, please contact us at ARC-DL-GeneLab-sequencing-group@mail.nasa.gov.
