# AMG25: A Dataset for APT Malware Group Attribution

Significant efforts were dedicated to the construction of a novel APT malware dataset called AMG25 (APT Malware with Group-label). The dataset comprises 5188 malware samples belonging to 25 distinct malware groups. Each APT group in our dataset consists of more than 30 samples, which ensures that we have sufficient data for robust train/test splitting and mitigates overfitting issues caused by limited training samples. Table2 illustrates the 25 APT groups present in our dataset along with the corresponding number of malware samples. During the following experiments, we split this dataset into training and testing subsets according to the ratio of 9: 1.

To create the dataset, we initially compiled a list of APT malware, including their MD5 hashes and group labels, by utilizing public threat intelligence sources. Furthermore, the group labels underwent manual verification by security analysts employed at a renowned security company in China. Subsequently, we proceeded to gather the malware samples associated with the MD5 hashes listed, sourcing them from VirusSign . Furthermore, we developed a feature analysis tool to extract statistical features, as outlined in Table1, for each malware sample. These features were then converted into gray-scale images. We are releasing the malware dataset, which includes the APT group label and hash value for each malware file, along with its corresponding gray-scale feature image.
  

## Citation

If you use this dataset in your research, please cite our paper on TDSC’2024:

#### Yuxia Sun; Shiqi Chen; Song Lin; Aoxiang Sun; Saiqin Long; Zhetao Li. MGAP3: Malware Group Attribution Based on PerceiverIO and Polytype Pre-Training[J]. IEEE Transactions on Dependable and Secure Computing, 2024. DOI: 10.1109/TDSC.2024.3418958. (2024.7.8 Early Access )

####[Abstract] To create the dataset, we initially compiled a list of APT malware, including their MD5 hashes and group labels, by utilizing public threat intelligence sources. Furthermore, the group labels underwent manual verification by security analysts employed at a renowned security company in China. Subsequently, we proceeded to gather the malware samples associated with the MD5 hashes listed, sourcing them from VirusSign . Furthermore, we developed a feature analysis tool to extract statistical features, as outlined in Table1, for each malware sample. These features were then converted into gray-scale images. We are releasing the malware dataset, which includes the APT group label and hash value for each malware file, along with its corresponding gray-scale feature image.
