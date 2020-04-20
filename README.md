# MRI Programming Task Sheet #1
**Supervision:** <span style = "color: red;"> Dr/ Inas Ahmed Yunis </span> 

## Information

***Team Members***

    Name: Marwa Abdallah
    Sec: 2
    BN: 28

    Name: Menna Allah Hamdy
    Sec: 2
    BN: 35

    Name: Fady Tadros
    Sec: 2
    BN: 13

    Name: Mostafa Yehia
    Sec: 2
    BN: 33

## Requirements to run the code
***The following libraries should be installed first***

    pillow library (PIL)
        pip install pillow
    qutip library
        pip install cython
        pip install qutip
    sympy library
        pip install sympy

## Equations
**Magnetic Moment Equation1**
> <span style="color: red;"> *µ = Gama * J* </span>

    µ is the magnetic moment vector
    Gama is the gyromagnetic ratio
    J is the angular momentum

**Magnetic Moment Equation2**
> <span style="color: red;"> *µ = Gama * (h_bar * sqrt(I * (I + 1)))* </span>

    I is the spin quantum number
    h_bar is Planck's constant (h) divided by 2 pi

**Bulk Vector Equation**
> <span style="color: red;"> *M_vector = Sum(n = 1 to Ns){ µn_vector }* </span>

    M is the bulk magnetization vector
    Ns is the number of spins
    µ are the magnetic moment vectors

**Bloch Equation**
> <span style="color: red;"> *Mz = M0 * (1 - exp(-t / T1))*, </span> <span style="color: red;"> *Mxy = M0 * exp(-t / T2)* </span>

    M0: Static Magnetic Field
    Mz: Longatudinal Magnetization
    Mxy = Transverse Magnetization
    T1: Recovery Time
    T2: Decay Time

# Results for Task2

***Recovery time for CSF Tissue***
> ![Recovery](Results/T1(CSF).jpg)

***Relaxation time for CSF Tissue***
> ![Relaxation](Results/T2(CSF).jpg)

***K-Space for phantom***
> ![Fourier](Results/Phantom_FT.jpg)