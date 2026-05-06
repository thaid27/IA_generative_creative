# IA générative créative

Ce GitHub a pour but de présenter mon expérience vis-à-vis des modèles génératifs à usage créatif. Plusieurs cas d’usage seront présentés ainsi que les méthodes employées dans des projets commerciaux concrets.

---

## 1. Génération d'image

L’IA générative peut tout d’abord être utilisée pour la génération d’images à un usage commercial varié, à partir de prompts et d'images de référence.

### Cas d'usage

- **Illustrations** pour une idée, assets commerciaux, character sheets, storyboards

<p align="center">
  <img src="https://github.com/user-attachments/assets/69ec4676-bde1-402c-bf4e-5b383a507a8a"
       width="208"
       height="312"
       alt="bbox">
</p>
<h4 align="center">Image d'illustration générée par IA pour une application de détection de déchets</h4>
<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/00693d24-6356-47ff-831b-279fa78ad326"
       width="662"
       height="354"
       alt="charactersheet">
</p>
<h4 align="center">Fiche de personnage générée par IA</h4>
<br>

- **Transfert de style**

<p align="center">
  <img src="https://github.com/user-attachments/assets/ea37c28d-797a-4f86-a0f1-ca47f059bf9f"
       width="595"
       height="229"
       alt="stylestransfert">
</p>
<h4 align="center">Image générée conservant le style</h4>
<br>

- **Édition d'images**

<p align="center">
  <img src="https://github.com/user-attachments/assets/abe2b393-0814-4099-b0a4-29a336731db8"
       width="569"
       height="307"
       alt="EditAI">
</p>
<h4 align="center">Insertion d'un asset dans une image</h4>
<br>

### Technologies utilisées

#### En local

Outils / plateformes utilisés :
- ComfyUI, interface nodulaire
- Python pour l’implémentation de modèles de recherche (GitHub)

Modèles utilisés :
- Flux Dev, Krea, Klein (GGUF)
- Stable Diffusion
- Qwen-Edit

#### Sur le cloud

Outils / plateformes utilisés :
- Plateforme propriétaire de l'entreprise
- Krea

Modèles utilisés :
- Flux-Krea
- SeaDream
- NanoBanana

---

## 2. Génération de vidéos

L’IA générative peut aussi générer des vidéos à partir de prompts, d’images de référence, de contenu audio ou d’autres vidéos.

### Cas d'usage

- Vidéos commerciales

<p align="center">
  <img width="640" height="360" alt="video1" src="https://github.com/user-attachments/assets/03f3f273-15c0-4766-baf8-7824642ecf18" />
  <img width="640" height="360" alt="video2" src="https://github.com/user-attachments/assets/787fb48d-7d38-4419-acfa-b50c7219ec6c" />
</p>
<h4 align="center">Exemples de plans générés par IA</h4>
<br>

- Contenu original (IA influenceur)

<p align="center">
  <img width="537" height="417" alt="storyboard" src="https://github.com/user-attachments/assets/6b03693d-5500-4c3e-9e0e-13d341eb9887" />
</p>
<h4 align="center">Création des images de référence pour la vidéo à partir du storyboard</h4>
<br>

https://github.com/user-attachments/assets/6a17ac30-77ff-416b-8fe1-b28b7e185e51

<h4 align="center">Génération de vidéo avec voix</h4>
<br>

Résultat final : [vidéo TikTok](https://www.tiktok.com/@nhm_abudhabi/video/7574052140268735751)

### Technologies utilisées

#### En local

Outils / plateformes utilisés :
- ComfyUI, interface nodulaire

Modèles utilisés :
- LTX
- Wan-2.2, Wan-2.2 Animate (avec audio)

#### Sur le cloud

Outils / plateformes utilisés :
- Plateforme propriétaire de l'entreprise
- Krea
- Wan
- Kling

Modèles utilisés :
- Veo 3
- Wan 2.2, 2.5 (avec audio)
- Kling 2.5 (avec audio)

---

## 3. Génération d'audio

L’IA générative peut aussi générer des voix afin d’accompagner les vidéos ou de s’en servir comme point de départ de la génération.

### Cas d'usage

- Voice-over
- Voix utilisée comme base pour la génération
- Génération de musique

### Technologies utilisées
- Hume
- ElevenLabs
- Python

---

## 4. Exploration de nouvelles modalités

L’IA peut aussi permettre d’offrir de nouvelles expériences inédites.

- Génération de modèles 3D à partir d'images

<p align="center">
  <img width="297" height="443" alt="base" src="https://github.com/user-attachments/assets/9f172e1b-c99d-48c6-8cfa-e4990cdf8ed2" />
</p>
<h4 align="center">Image de base</h4>

<p align="center">
  <img width="640" height="616" alt="3d" src="https://github.com/user-attachments/assets/58e48797-1c43-4bec-9b5d-600e2360a47b" />
</p>
<h4 align="center">Modèle 3D généré</h4>

**Technologies utilisées** : Hunyuan3D de Tencent

- Génération de mondes 3D navigables à partir d'images

<p align="center">
  <img width="598" height="386" alt="world" src="https://github.com/user-attachments/assets/6acd9f3b-956c-4a17-98f5-61f3ee6b7dbe" />
</p>
