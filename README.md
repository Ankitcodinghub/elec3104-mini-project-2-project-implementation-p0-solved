# elec3104-mini-project-2-project-implementation-p0-solved
**TO GET THIS SOLUTION VISIT:** [ELEC3104 Mini Project 2-Project Implementation P0 Solved](https://www.ankitcodinghub.com/product/elec3104-p0-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124502&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ELEC3104 Mini Project 2-Project Implementation P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
TLT-Level 2 Project Implementation

✓ For this project, you should implement a digital model of the peripheral auditory system comprising of a model of the outer ear and the middle ear (from TLT Level 1) and the transmission line mode of the cochlea (TLT Level 2).

✓ The transmission line model of the cochlea can be implemented as a cascade of many band-pass filters. Assignment Project Exam Help

Inner ear (Cochlea)

A longitudinal section of an uncoiled cochlea

TLT-Level 2 Project Implementation: Cochlear Modelling

• A simple electrical model of a section of the BM is shown below figure below.

Pressure and Displacement Transfer Functions

✓The Voltage or Pressure transfer function of the isolated section can be obtained as follows:

Low pass filter Resonant pole Resonant zero

Assignment Project Exam Help

Frequency Response – one section of the membrane

Low pass filter Resonant pole Resonant zero

Frequency Response – one section of the membrane

Frequency Response of Displacement

Transfer Function of a section

Low pass filter Resonant pole

Displacement Transfer Function

Digital filter model of the basilar membrane

✓ A digital filter model of the basilar membrane can be obtained by transforming the analogue filter equation (given below) to an equivalent digital filter equation.

✓ The impulse response of the Basilar Membrane (BM) is an important property and it should be preserved in the digital filter model of the BM. So use impulse invariant transformation and is given by:

1 1

𝑠+𝑎→ 1−𝑒−𝑎𝑇𝑧−1; T – sampling period

✓ On applying the impulse invariant transformation, the pressure transfer function in digital domain can be Assignment Project Exam Help obtained:

✓Where 𝑎0, 𝑎1, 𝑎2, 𝑏1, 𝑎𝑛𝑑𝑏2 are the digital filter coefficients;

Digital filter coefficients

𝒂𝟏 = 𝟐𝒆−𝒑𝟏 𝑻cos(𝒒𝟏𝑻); 𝒂𝟐 = 𝒆−𝟐𝒑𝟏 𝑻; 𝝎

𝒑𝟏 = 𝟐𝑸𝒛𝒛; 𝒒𝟏 = 𝒑𝟏 𝟒𝑸𝟐𝒛 − 𝟏 ;

𝒃𝟏 = 𝟐𝒆−𝒑𝟐 𝑻cos(𝒒𝟐𝑻); 𝒃𝟐 = 𝒆−𝟐𝒑𝟐 𝑻; 𝝎

𝒑𝟐 = 𝟐𝑸𝒑𝒑 ; 𝒒𝟐= 𝒑𝟐 𝟒𝑸𝟐𝒑 − 𝟏 ;

Sampling frequency (fs) = 48 kHz, T = 1/ fs

𝒂𝟎 = (𝟐 − cos𝜽𝒄) − (𝟐 − cos𝜽𝒄)𝟐 − 𝟏 ;

𝜽𝒄 𝑖𝑠 𝑡ℎ𝑒 3dB cut-off frequency of the low pass filter (choose 𝜽𝒄 = 1.4 * 𝝎𝒛)

✓ In each section, pressure is converted into displacement of the basilar membrane and transmitted to the

following section. This leads to two transfer functions, one relating the output pressure, Assignment Project Exam Help 𝑉𝑜 𝑛 , and the input pressure, 𝑉𝑖 𝑛 , and the other relating the output displacement, 𝑉𝑚 𝑛 to the input pressure.

One can see that the displacement transfer function is contained in the pressure transfer function and hence a simple cascade arrangement is sufficient to represent the cochlear model

Transmission Line Model of the Cochlea

✓ The basic model of the cochlea is a transmission line model in which the basilar membrane is modelled as a cascade of 128 low pass filters, notch filters and resonators as shown below. Assume a sampling frequency of 48 kHz.

Transmission Line Model

✓ Each digital filter section in the model above represents a section of the basilar membrane (tuned to a specific frequency) with 128 sections representing the entire basilar membrane.

✓ A stimuls representing pressure at the ear drum (after the outer ear model) is the input to the model shown in the figure above. This stimulus then moves along the transmission line as a travelling wave corresponding to the pressure in the cochlear fluid.

Selection of Frequency Scale

✓ The model considers the BM length to be 3.5 cm.

✓ If the membrane is simulated using 128 digital filters connected in cascade then the section length (∆𝑥) and the frequency ratio between adjacent sections are constant throughout. That is ∆𝑥 = 3.5/128 = 0.0275 cm;

✓ [𝑓[𝑝𝑓𝑝]𝑖]+𝑖1 =(20000(20000) 10) 10−0.−6670.667(𝑥+𝑥∆𝑥) = 100.667∆𝑥 = 1.0429

Filter number Distance (cm) Frequency(fp)

1 0 kHz

66 1.777 1304.79 Hz

128 3.4727 96.553 Hz

Assignment Project Exam Help

DISPLACEMENT DISPLACEMENT DISPLACEMENT

OUTPUT 1 OUTPUT i OUTPUT 128

Implementation – Step 1

✓ Number of filters N = 128; Length of the BM = 3.5 cm. ∆𝑥 = = 0.0273 𝑐𝑚

✓ 𝑥 = 0, ∆𝑥, 2∆𝑥, 3∆𝑥, … … … .Assignment Project Exam Help, 127∆𝑥; 𝑹𝒆𝒔𝒐𝒏𝒂𝒏𝒕 𝒇𝒓𝒆𝒒𝒖𝒆𝒏𝒄𝒚: 𝒇𝒑(𝒏) = (𝟐𝟎𝟎𝟎𝟎 ) 𝟏𝟎−𝟎.𝟔𝟔𝟕𝒏𝚫𝒙

Filter No (𝒏) Distance (𝑥) cm 𝒇𝒑 𝒏 : Resonant Frequency (Hz)http 𝒇𝒑 𝒏 s://powcod𝒇𝒑 𝒏+𝟏 𝒇𝒛 𝒏 : Resonant ze er.com (Notch filer) ro (Hz)

1 0 𝑓𝑝 1

= 20000

Ad 𝑓𝑝(1)

= 1.0429 d We𝑓𝑝(2)Chat powcod𝑓𝑧 1 = 1.0429×𝑓𝑝 1

er = 20858

2 ∆𝑥 𝑓𝑝 2

= 19177 𝑓𝑝(2)

= 1.0429

𝑓𝑝(3) 𝑓𝑧 2

= 1.0429×𝑓𝑝 2

= 20000

3 2∆𝑥 𝑓𝑝 3

= 18389 𝑓𝑝(3)

= 1.0429

𝑓𝑝(4) 𝑓𝑧 3

= 1.0429×𝑓𝑝 3

= 19178

4 3∆𝑥 𝑓𝑝 4

= 17633 . .

. . . .

128 127∆𝑥 𝑓𝑝 128 = 96.55

– 𝑓𝑧 128

= 1.0429×𝑓𝑝 128 =100.70

Implementation – Step 2

✓ Calculate the quality factor values, 𝑄𝑝 and 𝑄𝑧; and bandwidths, 𝐵𝑊𝑝 and 𝐵𝑊𝑧.

✓ 𝑄𝑝 varies linearly from 10 (first filter) to 5.5 (128th filter)

✓ 𝑄𝑧 varies linearly from 22 (first filter) to 12 (128th filter)

✓ You can change these around and observe what happens but ensure 𝑄𝑧 &gt; 𝑄𝑝. ✓𝐵𝑊𝑝 𝑛 = 𝑄𝑓𝑝𝑝 𝑛𝑛 and 𝐵𝑊𝑧 𝑛 = 𝑄𝑓𝑧Assignment Project Exam Help𝑧 𝑛𝑛

Filter No (𝒏): 𝒇𝒑 𝒏 in Hz 𝑸𝒑 𝒏

A 𝑩𝑾𝒑 𝒏 in

Hz

dd We 𝒇𝒛 𝒏 in Hz

Chat po 𝑸𝒛 𝒏

wcoder 𝑩𝑾𝒛 𝒏 in Hz

1 20000 10 2000 20858 22 948.1

2 19177 9.96 1925 20000 21.92 912.4

3 18389 9.93 1852 19178 21.84 878.0

. . . . .

128 96.55 5.5 17.56 100.70 12 8.4

Design Criteria

✓ In order to simulate the basilar membrane accurately with the transmission line model, it is critical that the complex zero frequency is slightly higher than the resonant frequency of the preceding resonator (complex pole filter).

✓ Selection of frequency scale: The ratios of the resonant frequencies of two adjacent sections are always constant and equal to 1.0429. i.e., the resonant frequency of the 𝑖𝑡ℎ section is 1.0429 times the resonant frequency of the 𝑖 + 1𝑡ℎ section.

✓ From experiments it is known that the Q values (quality factor) for the complex pole section, Assignment Project Exam Help 𝑄𝑝, go from 10 (1st filter) down to 5.5 (128th filter). You can interpolate linearly for the intermediate filters.

interpolate linearly for intermediate filters.

✓ For each section, 𝑄𝑧 &gt;𝑄𝑝

𝑓𝑝

✓ 𝐾 is chosen as the ratio of complex pole frequency to the complex zero frequency (K = , 𝐾 &lt; 1).

𝑓𝑧

✓ The cut-off frequency of the low pass filter can be chosen as follows: 𝒇𝒄 = 1.4 * 𝒇𝒛

✓ Note that this model gives the basilar membrane displacement without taking into account fluid coupling. In order to take fluid coupling into account you must apply the spatial differentiation (TLT Level1 slide 12).

✓ Use impulse invariant transformations (as outlined earlier) to design the digital filters.

Filter Number 𝒇𝒑 (Hz) 𝒇𝒛 (Hz) 𝑸𝒑 𝑸𝒛 𝑩𝑾𝒑(Hz) 𝑩𝑾𝒛 (Hz)

1 20000 20858 10 22 2000 948.1

2 19177 Add W20000 eChat 9.96 powco21.92 der1925 912.4

3 18389 19178 9.93 21.84 1852 878.0

. . . . .

128 96.55 100.70 5.5 12 17.56 8.4

Implementation – Step 3

Filter Number 𝑲 𝑮𝟎 𝒂𝟎 𝑮𝒑 𝒃𝟏 𝒃𝟐 𝑮𝒛 𝒂𝟏 𝒂𝟐

1 0.9589 0.8137 0.1863 3.2863 -1.5167 0.7697 0.2729 -1.7514 0.9130

2 0.9589 0.8199 0.1801 3.1975 -1.4202 0.7773 0.2798 -1.6574 0.9160

3 0.9589 0.8242 0.1758 3.0960 -1.3113 0.7847 0.2885 -1.5473 0.9189

.

.

128 0.9589 0.0183 0.9817 0.0002 1.9975 0.9977 5759 1.9985 0.9987

If your implementation is right, you should get these parameter values for the selected filters if you started with the same assumptions

Implementation – Step 4

✓ Digital filtering in the time domain for following inputs (sampled at 48kHz). You can use filter() in MATLAB to implement filtering.

✓ Impulse

✓ single sinusoid – Try initially with 1kHz, then others of your choice.

✓ Make sure you obtain all the 128 displacement outputs and 128 pressure outputs for each input signal. You can store these as 2 matrices with 128 columns and as many rows as there are samples in the input signal.

✓ From the impulse responses of each section, obtain the magnitude response (take FFT of the impulse response) and Assignment Project Exam Help make sure it is what you expect.

that time.

✓Note that spatial differentiation is carried out across columns (within each row).

Spatial Differentiation

✓ Spatial differentiation of the membrane displacement represents coupling between the cilia of the inner hair cells, through the fluid in the subtectorial space.

✓ Spatial differentiation refers to taking the derivative with respect to the position (along the basilar membrane). A discrete model is given by:

𝑑𝑚[n]=𝑠𝑚[n]- 𝑠𝑚+1[n]

{𝑒. 𝑔. 𝑑1[n]=𝑠1[n]- 𝑠2[n]}

✓ The second spatial differentiation is given by:

𝑒𝑚[n]=𝑑𝑚[n]- 𝑑𝑚+1[n]

{𝑒. 𝑔. 𝑒1[n]=𝑑1[n]- 𝑑2[n]}

Spatial Differentiation

✓ If your implementation is on the right track, you should observe the following impulse responses (roughly) at different sections of the membrane. Look at the membrane displacements when giving an impulse input.

✓ If your implementation is on the right track, you should observe the following magnitude response (roughly) at the appropriate section of the basilar membrane with and without spatial differentiation.

✓ If your implementation is on the right track, given a sinusoidal input, you should observe the following displacement (after two spatial differentiation) plotted against section number. As expected the membrane should exhibit activities up to the appropriate resonant section (where it shows maximum displacement) and no appreciable activity thereafter.

TLT level 2 Final Validation:

1. Apply a signal which is a sum of three sinusoids (Try a sum of a low frequency, a mid frequency and a high frequency sinusoid), 1000-2000 samples, of equal amplitude and frequencies of your choice, to the input of the cochlear model.

2. Plot membrane displacement (in one figure):

i. Without spatial differentiation ii. With one spatial differentiation iii. With two spatial differentiation

3. Explain your results to your lab demonstrator.

✓ If you plot the pressure outputs of different sections at a series of regular time steps (superimpose them on the same plot), you should observe something similar to the following.

Reflection

You should reflect on your project to see the following:

✓ What is the function of the basilar membrane and how does it respond to various input stimuli?

✓ What will happen if you include the outer and middle ear models at the input of the transmission line model of the cochlea in terms of hair cell output?

✓ What is the effect of spatial differentiation on the basilar membrane displacement?Assignment Project Exam Help

✓ What is the effect of the Q factors of your filters on the overall model? And what is the function of the complex zeros in your model?
