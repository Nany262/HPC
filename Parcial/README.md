**Segundo Parcial HPC:**

Presentado por:
- Angie Vanessa Penagos Rios
- Diego Alejandro Valencia
- Daniela Zuluaga Ocampo 

**Para ejecutar en el cluster:**
```bash
  cmake -DCUDA_USE_STATIC_CUDA_RUNTIME=OFF .
  make
  sbatch imagen.sh
```

**Para copiar imagen del cluster**
```bash
  scp -P 4000 usuario@dominio:rutaArchivo nuevaUbicación 
```
