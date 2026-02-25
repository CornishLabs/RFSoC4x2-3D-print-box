# RFSoC4x2-3D-print-box
A parametetrically designed box for the RFSoC 4x2, made with Autodesk Fusion.
Has M3 heatset inserts for board mounting, and lid fastening. This box only exposes the connectors we need, so please modify as necessary.

We print our boxes with PETG-CF on a Bambu Lab H2S. PLA is not recommended due to the heat the RFSoC board produces.

Our boxes were printed with 100% infill out of concern for the heatset inserts not having anything to push against on insertion, therefore
we recommend this, however this may be an abundance of caution. It did not add much time to the print time.

> [!NOTE]  
> A user @slwatkins has kindly contributed a solidworks conversion `RFSoC-box-v4-mass-print.SLDASM`, however I don't have the software to
> test this or keep it updated if I ever change the f3z file so treat this as an un-updated dependency past this commit.

7 (board) + 4 (lid) + 6 (optional box mount) = 17 heat set M3 inserts per box.
Lid needs M3 countersunk screws.
We use M3 socket cap screws for the board.

Designed for heat set M3 inserts with 4.1mm hole diameter, and 5.8mm length.

Extra holes on front panel are for insulated 50 ohm BNC Panel Mount Socket - Solder Termination.

![RFSoC box assembly GIF](./fusion_pingpong_slow.gif)
![Birdseye](./birdseye.jpg)
![empty](./cornerempty.jpg)
![full](./cornerfull.jpg)
![withlid](./cornercomplete.jpg)

 Copyright (C) 2025 Tom Hepworth
