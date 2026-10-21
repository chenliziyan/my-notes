## Circular Motion
- **Uniform Circular Motion**
  - motion in a circle with constant speed
- **Radian**: 
  - The angle subtended at the centre of a circle by an arc equal in length to the radius of the circle (1 radian: arc = radius)
- **Angular Displacement** $ \theta $
  - The change in angle, in radians, of a body as it rotates around a circle
- **Angular Speed** $ \omega $
  - Rate of change of angular **displacement** with respect to time
  - scalar
- **Centripetal Force** 
  - a resultant force towards the centre of the circle required to keep the body in uniform circular motion
  - 产生 circular acceleration
- **Centripetal Acceleration** $\alpha$
  - The acceleration of the object towards centre of circle when the object is in uniform circular motion

1. 圆周运动中：
   1. 角速度恒定，角速率变化
   2. 向心力/向心加速度（指向圆心） 垂直于 线速度（切线） 
2. 公式：
   1. $v = r\omega$
   2. $ \alpha = \frac{v^2}{r} = r{\omega}^2$
   3. $F = \frac{mv^2}{r} = mr{\omega}^2$

## Gravitational Fields
- **gravitational field**
  - a region of space where a **mass** experiences a force
  - direction: centre of mass
  - attractive
- **Gravitational Field Strength** $g$
  - The force per unit mass acting on a small mass at that point
- **Newton's Law of Gravitation**
  - the gravitational force between 2 point masses is proportional to the product of masses and inversely proportional to the square of their seperation
- **Gravitatioal Potential** $ \phi (Jkg^{-1})$ 
  - Work done per unit mass in bringing a small mass from infinity to that point
- **Gravitational Potential Energy** $E_p$
  - Energy an object possesses due to its position in gravitaional field
- **Gravitational Potential Energy of System**
  - The work done to assemble the system from infinite separation of the components of the system

1. 注意：
   1. 引力势是负值，随距离增加而增加，在无限远处为0
   2. 引力势能是负值，随距离增加而增加，在无限远处为0 
2. 公式：
   1. $ g = \frac{W}{m} = \frac{GM}{r^2}$
   2. $ F_G = \frac{Gm_1m_2}{r^2} $
   3. $ G = 6.67 \times 10^{-11}  Nm^2{kg}^{-2}$
   4. 卫星： $ v = \sqrt{\frac{GM}{r}}$
   5. $ g \propto \frac{1}{r^2}$
   6. $ \phi = -\frac{GM}{r}$
   7. $W = m\Delta\phi$
   8. $E_p = -\frac{Gm_1m_2}{r}$

## Ocsillation
- **Displacement** $ x $
  - The distance and direction of an object from its equilibrium position.
- **Amplitude** $ x_0 / A $
  - The maximum magnitude of displacement from the equilibrium position.
- **Period** $ T $
  - The time taken for one complete oscillation.
- **Frequency** $ f $
  - The number of complete oscillations per unit time.
- **Angular Velocity** $ \omega $
  - The rate of change of phase with time.
  - unit: ```rad s⁻¹``` 
- **Simple Harmonic Motion** 
  - Acceleration is proportional to displacement
  - Acceleration is opposite in direction to displacement
- **Equilibrium Position**
  - The position at which the resultant force acting on the oscillator is zero.
- **Oscillation**
  - A repeated motion about an equilibrium position.
- **Damping**
  - The loss of energy from an oscillating system due to resistive forces.
  - **light**: Damping in which the system continues to oscillate with a gradually decreasing amplitude.
  - **Critcal**: Damping in which the system returns to its equilibrium position in the shortest possible time without oscillating.
  - **Heavy**: Damping in which the system returns to its equilibrium position without oscillating, taking longer than with critical damping.
- **Natural frequency**
  - The frequency at which a system oscillates freely when displaced from its equilibrium position.
- **Resonance**
  - Resonance occurs when a system is forced to oscillate at its natural frequency, resulting in a maximum amplitude of oscillation.

1. 注意
   1. 没有damping的话总机械能守恒
2. 公式：
   1. $ \omega = \frac{2\pi}{T} = 2\pi f$
   2. $ a = -{\omega}^2x$
   3. $ v = \pm \omega \sqrt{A^2 - x^2}$
      1. $v_{max} = \pm \omega A$ (at equilibrium)
   4. $E =  \frac{1}{2}m{\omega}^2A^2$

## Temperature
- **Temperature**
  - A physical quantity that determines the direction of net thermal energy transfer between bodies.
- **Thermal Energy**
  - The energy possessed by an object due to its temperature.
  - transfer: conduction/convection/radiation
- **Thermal Equilibrium**
  - When there is no net transfer of thermal energy between regions
  - both regions reach an equal temperature
- **Thermometric property**
  - A physical property of a substance that varies with temperature and can be used to measure temperature.
- **Absolute zero**
  - The lowest possible thermodynamic temperature
  - zero kelvin
- **Specific Heat Capacity** $c$
  - The energy required to raise the temperature of unit mass of a substance by 1 K without a change of state.
  - unit: ```Jkg⁻¹K⁻¹```
- **Specific Latent Heat** $L$
  - The energy required to change the state of unit mass of a substance without a change in temperature.
  - fusion: Solid to Liquid
  - vaporization: Liquid to Gas
  - unit: ```Jkg⁻¹```


1. 注意
   1. Thermister 热敏电阻：温度升高电阻降低；曲线 -> 需要校准
   2. specifc latent heat，vaporization 高于 fusion
      1. fusion: increase molecular separation -> flow over each others
      2. vapo: completely separate molecules -> no force of attraction -> more energy
2. 公式
   1. $Q=cm\Delta T$
   2. $Q = mL$

## Ideal Gas
- **mole**
  - The amount of substance containing as many particles as there are atoms in 12g of carbon-12
- **Avogadro constant** $N_A$
  - The number of atoms in 12 g of carbon-12
  - $ 6.02 × 10^{23} $ molecules per mol
- **Ideal gas**
  - A gas that obeys the equation \(pV=nRT\) at all temperatures and pressures.
- **Root-mean-square speed** $c_{rms} = \sqrt{\langle c^2\rangle}$
  - The square root of the mean of the squares of the speeds of the molecules.

1. 注意
   1. molar mass $M_r$ 单位：```g mol⁻¹``` $n = \frac{m}{M_r}$
   2. $n$ 是摩尔数，$N$ 是分子数
   3. 有赤石的一堆theory？
2. 公式
   1. $pV = nRT$  ```R = 8.31 JK⁻¹mol⁻¹```
   2. $ pV =  NkT$ ```k is Boltzman Constant```
   3. $ k = \frac{R}{N_A}$
   4. $\overline{E_k}=\frac32kT$
   5. $pV=\frac13Nm\langle c^2\rangle$

## Thermodynamics
- **Internal Energy** $U$
  - The sum of the randomly distributed kinetic and potential energies of the molecules in a system.
  - Determined by the state of the system.
- **KE of molecules**
  - Energy possessed by molecules due to their random motion.
- **Potential Energy of Molecules**
  - Energy associated with the relative positions of molecules and intermolecular forces.
- **First Law of Thermodynamics**
  - The increase in internal energy of a system is equal to the energy transferred to the system by heating plus the work done on the system. 
  - Conservation of energy.
- **Work Done by Gas**
  - Energy transferred from the gas to its surroundings when the gas expands against an external pressure.
- **Work Done on Gas**
  - Energy transferred to the gas when it is compressed by an external force.

1. 注意
   1. adiabatic - 无热量传递 \(q=0\)
   2. isothermal - 恒温，对于理想气体：$\Delta U = 0$
2. 公式
   1. $U = E_k + E_p$
   2. $\Delta U = q + W_{on}$
   3. $W_{by} = p\Delta V$  ```const p```
   4. $W_{on} = -p\Delta V$  ```const p```