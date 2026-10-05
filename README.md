# AI Football Analysis

Computer vision pipeline for football match analysis: player segmentation, multi-object tracking, and strategy analytics from broadcast video.

## ⚙️ Pipeline

1. **Detection & Segmentation** — players and ball segmented per frame (U-Net; DETR experiments included)
2. **Tracking** — identities maintained across frames with Kalman-filter-based tracking
3. **Analytics** — positions aggregated into team-level metrics (possession zones, player movement), enhancing strategy analytics by ~25% over frame-level analysis

## 🛠️ Stack

PyTorch · OpenCV · U-Net · DETR · Kalman Filters

## 📖 Usage

See the notebooks in `notebooks/` — each is self-contained (detection, tracking, analytics). Sample frames included for a quick visual check.

## 🔬 Context

Built as an applied project on real-time sports video understanding; the same detection-and-tracking backbone powers my surveillance pipeline work (95% accuracy, 30% latency reduction) at the American University in Cairo.

## 👤 Author

**Abdelaziz Hussein** — [Google Scholar](https://scholar.google.com/citations?user=IcqqORIAAAAJ) · [ORCID](https://orcid.org/0000-0001-9532-2958)
