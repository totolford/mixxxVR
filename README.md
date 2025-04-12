# Mixxx.VR 🎧🕶️  
*Une immersion VR dans le DJing, powered by Mixxx & Meta Quest 3*  

![Banner](assets/banner.png) *(Optionnel : ajoute une bannière visuelle)*  

## 📌 **Description**  
**Mixxx.VR** est une adaptation open source de [Mixxx](https://mixxx.org/) pour la **réalité virtuelle** (Meta Quest 3).  
- 🎛️ **Table DJ 3D interactive** avec platines, mixer et effets.  
- ✋ **Contrôles naturels** via manettes VR.  
- 🔌 **Connecté à Mixxx** via OSC/MIDI pour un traitement audio réel.  

*Objectif* : Recréer l'expérience physique d'un setup DJ en VR, sans sacrifier la puissance de Mixxx.  

---

## 🚀 **Fonctionnalités (Objectifs)**  
| Fonctionnalité               | Statut       |  
|------------------------------|-------------|  
| Aucun ajout    | Aucun ajout |  


---

## 🛠️ **Technologies**  
- **Moteur VR** : Unity 2022 + XR Interaction Toolkit *(ou Unreal Engine 5)*  
- **Communication** : OSC (Open Sound Control) → [Mixxx OSC Wiki](https://github.com/mixxxdj/mixxx/wiki/OSC-Scripts)  
- **Modèles 3D** : Blender (assets custom) / Sketchfab  
- **Hardware cible** : Meta Quest 3 (mode standalone + PC VR)  

---

## 🧑‍💻 **Installation (Développeurs)**  
### Prérequis  
- Unity 2022.3+ ou Unreal Engine 5.2+  
- SDK Meta Quest (pour le déploiement)  
- Mixxx 2.4+ (avec OSC activé)  

### Étapes  
```bash
git clone https://github.com/tonusername/Mixxx.VR.git  
cd Mixxx.VR  
# Ouvrir le projet dans Unity/Unreal  
