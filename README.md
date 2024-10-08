# Theory of double-kink nucleation in dilute BCC alloys
A. Ghafarollahi*, W.A. Curtin

EPFL

alireza.ghafarollahi@gmail.com

## Summary

Yielding in pure BCC metals and dilute substitutional alloys occurs by double-kink nucleation and propagation along screw dislocations. At low temperatures, the yield stress is controlled by double-kink nucleation. Here, an analytical statistical model is presented to predict the stress- and length-dependent double-kink nucleation barrier in dilute BCC alloys solely in terms of the double-kink process in the pure metal and the solute/screw-dislocation interaction energies in the dilute alloy. __Consistent with early literature, dilute alloying always reduces the double-kink nucleation barrier (softening) independent of solutes or matrix.__ 

The model is extensively validated via simulations in model Fe-Si alloys described by interatomic potentials. The model is then compared to experiments on real Fe-Si, W-Ta, and W-Re alloys, showing qualitative agreement consistent with the accuracy of the inputs. A cross-over from the dilute limit to the non-dilute limit, where there is hardening, is analyzed using the present theory and the non-dilute theory of 
[Maresca-Curtin](https://www.sciencedirect.com/science/article/abs/pii/S1359645419306676). The analysis for Fe-Si is consistent with a cross-over at ~2-3 at.% Si, as observed experimentally, and qualitatively consistent with W-Ta and W-Re. 

The present theory plus the recent theory of [Maresca-Curtin](https://www.sciencedirect.com/science/article/abs/pii/S1359645419306676) together provide a coherent predictive framework for strengthening of screw dislocations over the full range of concentrations from extremely dilute ( ≪  1 at.%), to dilute (up to a few at.%) and non-dilute alloys including High Entropy Alloys.

![1-s2 0-S1359645420305061-fx1_lrg](https://github.com/user-attachments/assets/0751c198-f2c6-4155-82ef-9754bf08d743)

Figure 1: Doube-kink nucleation in a random solute environment. The fluctuations in the random solute environment create a distribution of solute energy changes. Here, we developed a fully theoretical model to predict the mean of this distribution from which the double-kink nucleation barrier versus stress can be predicted. Finally, by intersecting the imposed experimental barrier with the alloy barrier curve, the alloy strength can be computed.  

![Screenshot from 2024-09-30 18-29-35](https://github.com/user-attachments/assets/dceb18a9-0d6a-4533-9ecd-a46941d4d5b5)

Figure 2: Doube-kink nucleation theory predictions for $Fe_{1-x}-Si_{x}$ alloys.

### Code
The notebook file contains the functions and tools required to predict the yield stress in BCC dilute alloys controlled by double-kink nucleation.

#### Input parameters to the model
* __Stress-dependent double-kink transition state configurations in pure matrix__
* __stress-dependent double-kink nucleation barrier in pure matrix__
* __solute/dislocation interaction energy parameter $\Delta \tilde{E}_{p}$__.



### Original paper

Please cite this work as:
```
@article{ghafarollahi2020theory,
  title={Theory of double-kink nucleation in dilute BCC alloys},
  author={Ghafarollahi, Alireza and Curtin, William A},
  journal={Acta Materialia},
  volume={196},
  pages={635--650},
  year={2020},
  publisher={Elsevier},
url={[https://arxiv.org/abs/2409.05556](https://www.sciencedirect.com/science/article/abs/pii/S1359645420305061)}, 
}
```
