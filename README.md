# Dylans MCA project


# Week 1

The Theme that I chose to base my dataset around is Music from the Classical period. I choose this as it allows easier access to all 3 of the types of data required as music from this period is avaliable in abundance on sites such as IMLSP.

Key challenges to working with music/music related data is the restrictions that copyright place upon selection of music that can be analysed. Music in a public domain is completely avalilble for the purposes of the assessment, but music which is more mainstream, and more well known, is more difficult and harder to access. This makes music which is desirable to analyse and curate less readily avaliable, and can lead to the study and analysis of music which may not be as interesting or harder to curate a dataset around. In relation to pieces from the classical period, this music can be difficult to find an accurate and original recording of due to the limitations of the time. These classical pieces can then only be curated from updated modern versions of them rather than the original manuscript. Often sheet music of pieces that can be transcribed are under some level of copyright, so even though I have chose this period in order to avoid copyright it still may be difficult to actually do this. 

#  Week 2

During week 2, I imported a score into Musescore and corrected any issues that cropped up during the transcribing of the score. The piece was titled Sonata in C major by composer Ludwig AbeIlle. The main issues that occured with the transcribing of this particular score came with the lacking of dynamic markings that carried over from the original composition which led to a tedious process of implenting them step by step. 

Below is an example of the first fews bars of the piece before and then after it was transcribed by Musescore:

Before:


![ORIGINAL SONATA C](https://user-images.githubusercontent.com/113992031/206073438-6b670ec8-e1f3-4598-9e46-fdaa310c1282.PNG)



After:

![Transcribed Sonata C](https://user-images.githubusercontent.com/113992031/206073453-fa552d37-42d2-4423-bfb9-e40c2b255183.PNG)

Below is my effort to correct the sheet music to the best of my ability:

![Capture](https://user-images.githubusercontent.com/113992031/206827098-444c6ac7-a34c-4b7a-98e5-3ce51e425660.PNG)



# Week 3

This week introuced the Verovio viewer tool, and how it can be used to electronically display scores online. The link below will display my transcribed score online via the verovio viewer, along with some comments on the differences and advantages that XML and MEI files respectively have.

https://dtm-23.github.io/MCA-2022/verovio.html



# Week 4


During Week 4, I used python code to analyse an excel file which I created using jsymbolic. I used the code to create interesting data regarding my own chosen score, such as a pitch histogram which is displayed below.



<img width="368" alt="Myscorehistogram" src="https://user-images.githubusercontent.com/113992031/195601291-32e6d9a4-5245-47ab-a85e-a65c9cc3b3e4.png">

The Jsymbolic analysis of my piece also displayed intriguing results. I learned that the number of pitches within my piece was 31, along with the mean pitch being 65 and the most common pitch class being 7. 

I also uploaded the chord analysis of my piece into my data folder so it can be viewed. This file can be used for indepth analysis of individual chords, giving details on their step, octave, duration and note type.


# Week 5


This week saw the introduction of the importance of metadata. I went into my MEI file that I have been analysing across the last few weeks and annotaed the MEI header with key metadata regarding the piece. 

I identifed some key features of the sheet music and their associated elements witin the MEI documentation standards. Some had a 1 to 1 translation such as the composer element simply being <composer>. Other elements had different titles from what was expected, such as the location of a publisher being pubPlace. I did not modify all of the elements identifed in my schema however.

 
Below is a link to the edited file.

https://github.com/DTM-23/MCA-2022/blob/master/data/Week5task.mei





# Week 7


This week saw further editing of the week 5 file on enrich it with more metadata which was then displayed using the verovio viewer. CSS code was used to neatly format the metadata at the top of the piece to make it more readable. Below is a link to my edited score with the added metadata, I included an authority link to the copyright for the sheet music using the auth.URL line of code. 
 
 https://dtm-23.github.io/MCA-2022/MyMeta.html



# Week 8


During week 8, I found classical piano pieces which I could then analyse in the form of a spectrograph in sonic visualiser.

Example 1: Ludwig van Beethovan piano sonata No.2 Op.2 No.2

Spectrogram: 
![Beethovanspectro](https://user-images.githubusercontent.com/113992031/201108147-7b6e01fc-c0c2-4474-a218-49ed8efdd78c.png)

Waveform:
![Beethovanwaveform](https://user-images.githubusercontent.com/113992031/201108192-52ef8951-c0a5-42ff-9ace-bde5a48174f5.png)

Example 2: Jadin piano sonata 

Waveform:
![jadinwaveform](https://user-images.githubusercontent.com/113992031/201110120-f3f27c24-5a73-4b9d-a14f-7210391b8284.png)


Spectogram:
![Jadinspectro](https://user-images.githubusercontent.com/113992031/201110147-5cf14043-9fab-408e-8e73-b16728d4d42d.png)

Example 3: Ludwig Van Beethovan String Quartet No.1, Op.18 No.1

Waveform:
![Beethovanstrings](https://user-images.githubusercontent.com/113992031/201920131-eb332cfa-9742-4093-ac68-2e0a94a5a2e5.png)

Spectogram:
![beethovanstringsspectro](https://user-images.githubusercontent.com/113992031/201920165-4cbe4584-390b-42e8-a858-864b33199e3d.png)
 
 
An advantage held by the time-frequency based spectogram is that it shows the frequency content of a signal changing over time. The wave-based format does not provide this as it assumes that frequency is consistance throughout the track, and only provides time based information meaning its representation of a frequency signal is incomplete. 

 



# Week 9

During this lab session I took the 3 tracks that I used during the previous week and further analysed them using Sonic Visualiser. On top of the spectrogram generate for each track I also generated a MFCC along with a chromagram, along with saving the three as CSV files. Down below is the different panes generated. 

Beethovan piano sonata MFCC:

![BeethovansonataMFCC](https://user-images.githubusercontent.com/113992031/206925837-5a5ce2ce-80ec-475d-8ded-a3e5b5198613.png)

Beethovan piano sonata Chromagram:

![Beethovansonatachromo](https://user-images.githubusercontent.com/113992031/206925862-4149a3f6-a8f8-444f-becd-342bba30eacb.png)

 
 Jadin piano sonata MFCC:
 
 ![JadinMFCC](https://user-images.githubusercontent.com/113992031/206925991-a1fb7e25-c586-401c-82e5-e9410e67c0a5.png)

 Jadin piano sonata Chromagram:
 
 ![jADINchromo](https://user-images.githubusercontent.com/113992031/206925999-7318938f-d49c-4852-a6ed-707a2cccb3e7.png)

 Beethovan String Quartet MFCC:
 
 ![MFCCallegro](https://user-images.githubusercontent.com/113992031/206926093-f6fd8c4e-4d4a-4c81-8e4e-1c6fe71ca67c.png)

 Beethovan String Quartet Chromogram:
 
 ![Chromoallegro](https://user-images.githubusercontent.com/113992031/206926121-a9641d4e-4200-4cd9-a31e-0e236b46bf0e.png)
 
 
 Afterward, I used python notebook to create individual MFCC histograms for these 3 tracks which are seen below:
 
 Beethovan piano sonata histograms:
 
![BeethovanCSVhistrograms](https://user-images.githubusercontent.com/113992031/206926690-d1349be7-4562-42c4-9b0c-5a6c1f89fc0c.png)


 Jadin piano sonata histrograms:
 
 ![JadinMFCCHistrogram](https://user-images.githubusercontent.com/113992031/206926262-620e10a0-dec8-4402-b269-dfe8805c53b9.png)

 Beethovan string quartet histograms:
 
 ![AllegroMFCChistrograms](https://user-images.githubusercontent.com/113992031/206926297-b27343d4-117f-4eb7-a103-3a00216c9f9e.png)

 
 
 
 

 






















# Week 10



Part 1 of the final lab week involved generating a simularity matrix of the different chroma values of 9 tracks. Three of these tracks were replaced using my own three tracks used during weeks 8-9. From this, we can see how similar the features of these tracks are to that of the others inside the python notebook. Below is the resulting matrix:
 
 Matrix 1:
 
 ![sim matrix 1](https://user-images.githubusercontent.com/113992031/206927841-6df506cd-0683-4a27-97d8-663be18683e1.png)

 
 
 Matrix 2:
 
 ![download](https://user-images.githubusercontent.com/113992031/206927849-5bc89d4d-1a02-41cf-aeb2-dc84a2fc9bc8.png)
 
 
 Part 2 involved using my chosen piece from back in week 2 and transcribing the WAV file verison of it into musescore, allowing us to critical analyse the differences that the transcirption had. 
 
 Week 10 wav image:
 
 ![WEEK10WAVIMAGE](https://user-images.githubusercontent.com/113992031/206943839-5ef80d43-b6ca-4ec5-b6fb-9bf88fa7159d.png)

 
 Week 10 polyphonic transcription image:
 
 ![WEEK10POLYIMAGE](https://user-images.githubusercontent.com/113992031/206943857-468caecd-66b6-4742-aa86-223bcdc220a3.png)

 
 
 
 The polyphonic pane was then loaded into musescore, below is a comparsion between my  week 2 PDF transcription and the week 10 MIDI transcription.
 
 
 
 
 
 
 Week 2 transciption:
 
 ![Week2Sonatatrans-1](https://user-images.githubusercontent.com/113992031/206947325-1b778e83-8c5f-4e9d-bce6-25035b64323e.png)


![Week2Sonatatrans-2](https://user-images.githubusercontent.com/113992031/206947337-89b8298d-f48d-41c0-aa6d-ee9cb6dd71e3.png)




 
 Week 10 transcription:
 
 ![Week10transcription-1](https://user-images.githubusercontent.com/113992031/206943718-dcd1181b-e145-4792-9723-cb33136f2408.png)

 ![Week10transcription-2](https://user-images.githubusercontent.com/113992031/206943730-274d4262-3cfa-4062-b546-f08a2db2f5e8.png)

 ![Week10transcription-3](https://user-images.githubusercontent.com/113992031/206943745-d1378d90-cdf6-4957-aeec-b447764fa7df.png)


 
Whilst the original PDF transcription was quite inaccurate, the MIDI transcription is significantly more so. The week 10 transcription has stretched out the first 30 bars of the pieces across 3 entire pages, each line only containing 2 bars filled with inaccurate transcription of the piece. The key within the piece has also been changed entirely, with both clefs completely missing whilst 


