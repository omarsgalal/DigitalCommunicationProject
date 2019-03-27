# Digital Communciation Project
Simulate the performance of different modulation schemes,[BPSK](#a), [QPSK](#b), [FSK](#c), [QAM16](#d),[QAM64](#e) in an AWGN environment 


 # To reproduce the experiments and figures:
 1. Open matlab
 2. Type "bertool" in the matlab terminal
 3. In theoretical tap do the following:
    - put the Eb/No to -10:10
    - Channel type: AWGN
    - Modulation type: PSK or FSK or QAM based on needed modulation technique
    - Modulation order: 2 for BPSK and FSK, 4 for QPSK, 16 for QAM16, 64 for QAM64
    - click plot button
 4. In the Monte Carlo tap do the following:
    - put the Eb/No to -10:10
    - browse and choose the model based on Modulation type (BPSK.slx - QPSK.slx - FSK.slx - QAM16.slx - QAM64.slx)
    - BER variable name: BER
    - click run


# <a id="a"></a>Binary Phase Shift Keying (BPSK)
## Definition: 
BPSK is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ = 0 degree for binary 1 and θ = 180 degree for binary 0
In BPSK, only one sinusoid is taken as the basis function. Modulation is achieved by varying the phase of the sinusoid depending on the message bits.


## Scatter plot before noise:
![BeforeNoise](BPSK/beforenoise.png)
## Scatter plot after noise:
![AfterNoise](BPSK/afternoise.png)
## BER Graph
![BERGraph](BPSK/ber.png)


# <a id="b"></a> QPSK
## Definition: 
QPSK is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees). QPSK allows the signal to carry twice as much information as ordinary PSK using the same bandwidth

## Scatter plot before noise:
![BeforeNoise](QPSK/beforenoise.png)
## Scatter plot after noise:
![AfterNoise](QPSK/afternoise.png)
## BER Graph
![BERGraph](QPSK/ber.png)


## <a id="e"></a> FSK
### Definition: 
FSK is a frequency modulation scheme in which digital information is transmitted through discrete frequency changes of a carrier signal.

## Scatter plot before noise:
![BeforeNoise](FSK/beforenoise.png)
## Scatter plot after noise:
![AfterNoise](FSK/afternoise.png)
## BER Graph
![BERGraph](FSK/ber.png)



## <a id="c"></a>QAM16
### Definition: 
Quadrature amplitude modulation (QAM) is a technique used to transmit two digital bit streams or two analog signals by modulating or changing the amplitudes of two carrier waves so that they differ in phase by 90 degrees, a quarter of a cycle, hence the name quadrature. One signal is called the "I" signal and the other is the "Q" signal, which can be mathematically represented by a cosine and a sine wave, respectively.

## Scatter plot before noise:
![BeforeNoise](QAM16/beforenoise.png)
## Scatter plot after noise:
![AfterNoise](QAM16/afternoise.png)
## BER Graph
![BERGraph](QAM16/ber.png)


## <a id="d"></a>QAM64

## Scatter plot before noise:
![BeforeNoise](QAM64/beforenoise.png)
## Scatter plot after noise:
![AfterNoise](QAM64/afternoise.png)
## BER Graph
![BERGraph](QAM64/ber.png)