Project 2: Text Summarization Fine Tuning

1. Introduction


Model BERT, yang merupakan singkatan dari "Bidirectional Encoder Representations from Transformers," telah membuktikan kemampuannya dalam memahami konteks teks dengan lebih baik, termasuk dalam bahasa Indonesia. Untuk penelitian ini, kita akan menggunakan dataset dari Liputan 6, salah satu sumber berita terkemuka di Indonesia. Melalui penggunaan model BERT dan dataset ini dari Hugging Face, dalam codingan ini akan fokus pada proses evaluasi model BERT untuk meringkas text sesuai dataset.

Dataset 
Dataset memiliki dua varian: "canonical" dan "xtreme". Varian "xtreme" membuang seperangkat dev dan tes dokumen-ringkasan di mana ringkasan memiliki kurang dari 90% novel 4-gram (data pelatihan tetap sama dengan varian canonical).


2. Struktur Dataset

{
  'id': 'string',
  'url': 'string',
  'clean_article': 'string',
  'clean_article': 'string',
  'extractive_summary': 'string'
}


3. Data Fields

id: id dari sampel
url: url asal artikel
clean_article: artikel sebelum diringkas
clean_article: ringkasan abstrak
extractive_summary: ringkasan ekstraktif



4. Objective Project
- Menemukan model BERT terbaik untuk melakukan text summarization 
- menggunakan evalusi ROUGE untuk penilaian tiap model BERT


5. Contact
For more info contact me on LinkedIn : https://www.linkedin.com/in/mohammad-fitrah-giffari-885470142/
