## Get files

git clone --recurse-submodules https://github.com/RoboCoderJet/qmk_miryoku_aurora_corne.git
cd qmk_miryoku_aurora_corne
qmk setup RoboCoderJet/qmk_miryoku_aurora_corne

## Build steps

qmk compile -c -kb splitkb/aurora/corne/rev1 -km manna-harbour_miryoku -e CONVERT_TO=rp2040_ce -e MIRYOKU_NAV=INVERTEDT -e MIRYOKU_CLIPBOARD=WIN -e MIRYOKU_LAYERS=FLIP