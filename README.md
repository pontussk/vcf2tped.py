# vcf2tped.py
Convert VCF to PLINK tped and tfam.


###Example usages which will create myfile_out.tped and myfile_out.tfam files:

python vcf2tped.py myfile.vcf myfile_out

python vcf2tped.py myfile.vcf.gz myfile_out

#####Also possible to pipe to stdout:

python vcf2tped.py myfile.vcf.gz - > myfile_out.txt
