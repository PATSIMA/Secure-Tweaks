# Configuración de Prioridad de Procesos (Win32PrioritySeparation)

## Descripción

La clave de registro `HKLM\SYSTEM\CurrentControlSet\Control\PriorityControl\Win32PrioritySeparation` permite configurar la asignación de tiempo de CPU entre procesos de primer plano y segundo plano en sistemas Windows.

## Valores y Configuraciones

Cada valor combina tres parámetros: 
- Duración de tiempo de proceso (Corto/Largo)
- Tipo de asignación (Fijo/Variable)
- Impulso de primer plano (Sin impulso/Impulso medio/Alto impulso)

### Tabla de Configuraciones

| Decimal | Hexadecimal | Duración | Asignación | Impulso de Primer Plano |
|---------|-------------|----------|------------|------------------------|
| 42 | 2A | Corto | Fijo | Alto |
| 41 | 29 | Corto | Fijo | Medio |
| 40 | 28 | Corto | Fijo | Sin impulso |
| 38 | 26 | Corto | Variable | Alto |
| 37 | 25 | Corto | Variable | Medio |
| 36 | 24 | Corto | Variable | Sin impulso |
| 26 | 1A | Largo | Fijo | Alto |
| 25 | 19 | Largo | Fijo | Medio |
| 24 | 18 | Largo | Fijo | Sin impulso |
| 22 | 16 | Largo | Variable | Alto |
| 21 | 15 | Largo | Variable | Medio |
| 20 | 14 | Largo | Variable | Sin impulso |

## Referencias

- [Guru3D Forums](https://forums.guru3d.com/threads/faq-of-the-software-operating-systems-section.155424/#post-1451631)
- [UDC Computer Science Documentation](https://csit.udc.edu/~byu/UDC3529315/WindowsInternals-4e.pdf)

## Descargas
- [24-Hex](https://github.com/PATSIMA/Secure-Tweaks/blob/main/Win32PrioritySeparation/24-Hex.reg)
- [26-Hex](https://github.com/PATSIMA/Secure-Tweaks/blob/main/Win32PrioritySeparation/26-Hex.reg)
- [2A-Hex](https://github.com/PATSIMA/Secure-Tweaks/blob/main/Win32PrioritySeparation/2A-Hex.reg)
