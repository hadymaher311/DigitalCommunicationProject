# Digital Communication project

Simulation of the performance of different modulation schemes, BPSK, QPSK, FSK,
QAM(16-64) in an AWGN environment.

## Usage

1. Open Matlab
2. Open files with simulink
3. Tweek the AWGN channel Eb/No.
4. Type `bertool` in Matlab terminal.
5. Plot the theoretical figure.
6. In Monte Carlo tab choose the EbNo range, the scheme file and write `ber` in BER variable name then press run to get the graph.

## Files

```text
Project/
├── MODULATION_TYPE/
    ├── images/
    │   ├── MODULATION_TYPE.jpg
    │   ├── MODULATION_TYPE_fig.jpg
    │   ├── MODULATION_TYPE_with_raised.jpg
    │   └── MODULATION_TYPE_with_raised_fig.jpg
    ├── MODULATION_TYPE_with_raised.slx
    └── MODULATION_TYPE.slx
```

## BPSK

Binary Phase Shift Keying (BPSK) is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.

### Plot

- Scatter plot of BPSK before and after noise: <p align="center"><img src="./BPSK/images/BPSK.JPG" /></p>
- Scatter plot of BPSK with Raised-Cosinebefore and after noise: <p align="center"><img src="./BPSK/images/BPSK_with_raised.JPG" /></p>

### BER Graph

- BER graph of BPSK: <p align="center"><img src="./BPSK/images/BPSK_fig.JPG" /></p>
- BER graph of BPSK with Raised-Cosine: <p align="center"><img src="./BPSK/images/BPSK_with_raised_fig.JPG" /></p>

## FSK

Frequency Shift Keying (FSK) is the digital modulation technique in which the frequency of the carrier signal varies according to the digital signal changes. FSK is a scheme of frequency modulation.

### Plot

- Scatter plot of FSK before and after noise: <p align="center"><img src="./FSK/images/FSK.JPG" /></p>
- Scatter plot of FSK with Raised-Cosinebefore and  after noise: <p align="center"><img src="./FSK/images/FSK_with_raised.JPG" /></p>

### BER Graph

- BER graph of FSK: <p align="center"><img src="./FSK/images/FSK_fig.JPG" /></p>
- BER graph of FSK with Raised-Cosine: <p align="center"><img src="./FSK/images/FSK_with_raised_fig.JPG" /></p>

## QPSK

Quadrature Phase Shift Keying (QPSK) is a variation of BPSK, and it is also a Double Side Band Suppressed Carrier (DSBSC) modulation scheme, which sends two bits of digital information at a time, called as bigits.

### Plot

- Scatter plot of QPSK before and after noise: <p align="center"><img src="./QPSK/images/QPSK.JPG" /></p>
- Scatter plot of QPSK with Raised-Cosinebefore and  after noise: <p align="center"><img src="./QPSK/images/QPSK_with_raised.JPG" /></p>

### BER Graph

- BER graph of QPSK: <p align="center"><img src="./QPSK/images/QPSK_fig.JPG" /></p>
- BER graph of QPSK with Raised-Cosine: <p align="center"><img src="./QPSK/images/QPSK_with_raised_fig.JPG" /></p>

## QAM

Quadrature amplitude modulation (QAM) is the name of a family of digital modulation methods and a related family of analog modulation methods widely used in modern telecommunications to transmit information.

### 16 QAM

- Scatter plot of 16 QAM before and after noise: <p align="center"><img src="./QAM/images/16-QAM.JPG" /></p>
- Scatter plot of 16 QAM with Raised-Cosine before and after noise: <p align="center"><img src="./16 QAM/images/16 QAM_with_raised.JPG" /></p>

### BER Graph

- BER graph of 16 QAM: <p align="center"><img src="./QAM/images/16-QAM_fig.JPG" /></p>
- BER graph of 16 QAM with Raised-Cosine: <p align="center"><img src="./QAM/images/16-QAM_with_raised_fig.JPG" /></p>

### 64 QAM

- Scatter plot of 64 QAM before and after noise: <p align="center"><img src="./QAM/images/64-QAM.JPG" /></p>
- Scatter plot of 64 QAM with Raised-Cosine before and after noise: <p align="center"><img src="./64 QAM/images/64 QAM_with_raised.JPG" /></p>

### BER Graph

- BER graph of 64 QAM: <p align="center"><img src="./QAM/images/64-QAM_fig.JPG" /></p>
- BER graph of 64 QAM with Raised-Cosine: <p align="center"><img src="./QAM/images/64-QAM_with_raised_fig.JPG" /></p>

## autor

- Hady Maher