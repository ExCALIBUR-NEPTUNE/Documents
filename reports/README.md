# Report codes

Reports - numbering as file-name:
(ID Number)-(two letter code)-number(-optional version) , e.g.  2047356-TN-01-2.

### ID Number codes

* 2021000   Oxford Maths
* 2047352   UCL - see note
* 2047353   STFC
* 2047355   Warwick PIC
* 2047356   York and Exeter
* 2047357   Oxford Physics
* 2047358   York and Warwick
* 2048465   Exeter and Imperial
* 2048906   Exeter UQ

* 2053622   Kings and Imperial
* 2060042   Imperial and Kings
* 2057701   UCL Y3
* 2060049   STFC Y3
* 2057699   York and Warwick Y3

(UCL had only one number from Y2, but two grants UQ 2047352_1 and MOR 2047352_2)

### Letter Codes

* TN  technical note
* PS  monthly progress statement
* QR  quarterly report
* AR  annual report
* MN  minutes
* RP  any other technical report
* AD  any other admin document

The second number may be chosen by the grantee, use of consecutive increasing
small natural numbers for both this and the version is recommended.

# Table of contents

| Task                                   | Responsible Person(s)  |            Comments              |
|:---------------------------------------|:-----------------------|:--------------------------------:|
| **Call 1**                            |                        |                                  |
| 1.1 Generation of edge mesh            |     DM                 |                                  |
| 1.2 Surface mesh generation            |     DM                 |                                  |
| 1.3 Software development 1             |     DM                 |                                  |
| 1.4 Curvilinear mesh generation        |     DM                 |                                  |
| 2.1 Aniso 2D                           |     CC & SJS           |                                  |
| 2.2 Matrix-free Laplacian              |     DM                 |                                  |
| 2.3 Aniso preconditioning              |     DM                 |                                  |
| 2.4 Proxyapps                          |     DM                 |                                  |
| 3.1 Proxyapp coord                     |     CC & SJS           |                                  |
| 3.2 Training materials                 |     DM                 |                                  |
| 3.3 Coordination                       |     DM                 |                                  |
|                                        |                        |                                  |
| **Call 2**                            |                        |                                  |
| M3 Implicit field solver               |     TG                 |                                  |
| M4 Particle orbit solver               |     BM                 |                                  |
| M5 Low noise                           |     BM                 |                                  |
| M6 Codesign with SHP, gyro-averaging   |     BM                 |     [2047355-TN-01-3.pdf](2047355/TN-01.pdf)           |
|                                        |                        |                                  |
| **Call 3**                            |                        |                                  |
| D1.1 First report                      |     MV                 |     [2047352_1-TN-01-3.pdf](2047352_1/TN-01.pdf)        |
| M1.1 Select codes                      |     PVC                |                                  |
| D1.2 Final report                      |     MV                 |     [2047352_1-TN-01-4.pdf](2047352_1/TN-01.pdf)        |                             |
| M1.2 VVUQ evaluations                  |     PVC                |                                  |
| A1 Literature Review                   |     PVC                |                                  |
| D2.1 Initial workshop                  |     PVC                |                                  |
| D2.2 Final workshop                    |     PVC                |                                  |
| A2 Completion                          |     PVC                |                                  |
|                                        |                        |                                  |
| **Call 4**                            |                        |                                  |
| D1.1 Preliminary report                |     DeM                |     [2047352_2-TN-01-3.pdf](2047352_2/TN-01.pdf)        |
| M1.1 Select literature and codes       |     SG                 |                                  |
| D1.2 Final report                      |     DeM                |                                  |
| M1.2 ROM on toy                        |     SG                 |                                  |
| D2.1 Workshop 1                        |     SG                 |                                  |
| D2.2 Workshop 2                        |     SG                 |                                  |
| D2.3 Cost benefit for key codes        |     DeM                |                                  |
| M2.2 Engagement                        |     SG                 |                                  |
|                                        |                        |                                  |
| **Call 6, 2047356**                   |                        |                                  |
| 0.1 Community standards                |     PH                 |                                  |
| 0.2 Coordination FY21/22               |     EH & DD            | [2047356-TN-10-1.pdf](2047356/TN-10-1.pdf) |
| 0.3 Coordination FY22/23               |     PH                 |                                  |
| 1.1 2D elliptic, select test cases     |     BD                 | [2047356-TN-02-2.pdf](2047356/TN-02.pdf) |
| 1.2 Elliptic BOUT++                    |     BD                 |                                  |
| 1.3 Elliptic Nektar++                  |     DM                 | [2047356-TN-12-2.pdf](2047356/TN-12-2.pdf) |
| 1.4 Precondition 2D elliptic solvers   |     BD                 | [2047356-TN-06-1.pdf](2047356/TN-06-1.pdf) |
| 2.1 1-D fluid with UQ, select tests    |     BD                 |                                  |
| 2.2 1-D BOUT++ bc implementation       |     BD                 | [2047356-TN-07-1.pdf](2047356/TN-07-1.pdf) |
| 2.3 1-D Nektar++                       |     DM                 | [Nektar-1d-sol](https://github.com/ExCALIBUR-NEPTUNE/nektar-1d-sol) |
| 2.4 UQ 1 (BOUT++)                      |     SW                 | [2047356-TN-08-1.pdf](2047356/TN-08-1.pdf) |
| 2.5 UQ 2                               |     SW                 |                                  |
| 3.1 1-D +velocity, select tests        |     DD                 | [2047356-TN-11-1.pdf](2047356/TN-11-1.pdf) |
| 3.2 Phase space                        |     DD                 | [2047356-TN-11-1.pdf](2047356/TN-11-1.pdf) |
| 3.3 Timestepping                       |     DD                 | [2047356-TN-11-1.pdf](2047356/TN-11-1.pdf) |
| 4.1 1-D multispecies, select tests     |     BD                 | [2047356-TN-09-1.pdf](2047356/TN-09-1.pdf) |
| 4.2 Implement BOUT++                   |     BD                 |                                  |
| 4.3 DSL adoption                       |     SW                 | [2047356-TN-14-1.pdf](2047356/TN-14-1.pdf) |
| 5.1 2-D plasma, select tests           |     DM                 | [2047356-TN-13-2.pdf](2047356/TN-13-2.pdf) |
| 5.2 Proxyapp assessment                |     DM                 | [2047356-TN-13-2.pdf](2047356/TN-13-2.pdf) |
| 5.3 Roadmap to SHP/Nektar++            |     DM                 |                                  |
|                                        |                        |                                  |
| **Call 7**                            |                        |                                  |
| M1.1 Elliptics 1                       |     ES & ST            |     [2047353-TN-01-2.pdf](2047353/TN-01.pdf)          |
| M1.2 Elliptics 2                       |     ES                 |                                  |
| D1.1 Elliptics                         |     ES & ST            |                                  |
| M2.1 Hyperbolics 1                     |     ES & ST            |     [2047353-TN-01-2.pdf](2047353/TN-01.pdf)          |
| M2.2 Hyperbolics 2                     |     ES                 |                                  |
| D2.1 Hyperbolics                       |     ES & ST            |                                  |
| M3.1 SPAI                              |     ES                 |                                  |
| D3.1 SPAI                              |     VA, ES & ST        |     [2047353-TN-02-2.pdf](2047353/TN-02.pdf)          |
| 4.1 Coupled theory                     |     ES & ST            |                                  |
| 5.1 Coupled code 1                     |     ES & ST            |                                  |
| 5.2 Coupled code 2                     |     ES                 |                                  |
| D5.1 Coupled code 1                    |     ES                 |                                  |
| D5.2 Coupled code 1                    |     ES                 |                                  |
| 6.1 Code                               |     ES                 |                                  |
| 6.2 Uncoupled test 1                   |     ES & ST            |                                  |
| 6.3 Uncoupled test 2                   |     ES                 |                                  |
| 6.4 Coupled test 1                     |     ES & ST            |                                  |
| 6.5 Coupled test 2                     |     ES                 |                                  |
| 6.6 All  test                          |     ES                 |                                  |
| D6.1 Code                              |     ES                 |                                  |
| D6.2 Uncoupled test 1                  |     ES & ST            |                                  |
| D6.3 Coupled test                      |     ES & ST            |                                  |
| D6.4 Recommendations                   |     VA, ES & ST        |     [2047353-TN-03-3.pdf](2047353/TN-03.pdf)       |
|                                        |                        |                                  |
| **Call 8, 2047357**                   |                        |                                  |
| M1.1 1D parallel model periodic        |     FP                 |     [2047357-TN-01-2.pdf](2047357/TN-01.pdf)          |
| M1.2 Regimes, state-of-art models      |     FP                 |     [2047357-TN-03-2.pdf](2047357/TN-03.pdf)          |
| M1.3 Wall bcs                          |     FP                 |                                  |
| M1.4 2D model walls                    |     FP                 |                                  |
| M1.5 Analytic benchmarks for 2-D walls |     FP                 | [2047357-TN-12-2.pdf](2047357/TN-12-2.pdf) |
| M1.6 2D periodic                       |     FP                 |                                  |
| M1.7 2D with separatrix                |     FP                 |                                  |
| M1.8 3D electrostatic 1                |     FP                 |                                  |
| M1.9 3D electrostatic 2                |     FP                 |                                  |
| M1.10 3D electrostatic 3               |     FP                 |                                  |
| D1.1 Regimes, s-o-a models             |     FP                 |                                  |
| D1.2 1-D parallel periodic/wall bcs    |     FP                 |                                  |
| D1.3 2D model walls                    |     FP                 |                                  |
| D1.4 2D periodic                       |     FP                 |                                  |
| D1.5 2D with separatrix                |     FP                 |                                  |
| D1.6 3D electrostatic 1                |     FP                 |                                  |
| D1.7 3D electrostatic 2                |     FP                 |                                  |
| M2.1 1D drift-kinetic periodic 1       |     MB                 |                                  |
| M2.2 1D drift-kinetic periodic 2       |     MB                 |                                  |
| M2.3 1D std vs. moment                 |     MB                 |                                  |
| M2.4 1D std walls                      |     MB                 |                                  |
| M2.5 1D moment walls                   |     MB                 | [2047357-TN-10.pdf](2047357/TN-10.pdf) |
| M2.6 2D std walls                      |     MB                 |                                  |
| M2.7 2D moment walls                   |     MB                 |                                  |
| M2.8 2D model periodic                 |     MB                 |                                  |
| M2.9 Final report                      |     MB                 |                                  |
| D2.1 1D drift-kinetic proxyapp         |     MB                 |                                  |
| D2.2 1D drift-kinetic numerics         |     MB                 | [2047357-TN-10.pdf](2047357/TN-10.pdf) |
| D2.3 2D drift-kinetic proxyapp         |     MB                 |                                  |
| D2.4 2D drift-kinetic numerics         |     MB                 |                                  |
| D2.5 Proxyapps final report            |     MB                 |                                  |
|                                        |                        |                                  |
| **Call 9, 2047358**                   |                        |                                  |
| D1.1 Report h/w                        |     SW                 |                                  |
| D1.2 Report s/w                        |     GM                 |                                  |
| D1.3 Exascale I/O                      |     SW                 |                                  |
| M1 Survey of h/w and s/w               |     SW                 | [2047358-TN-01-2.pdf](2047358/TN-01-2.pdf) |
| D2.1 Testbed repo                      |     SW                 |                                  |
| D2.2 Assess systems                    |     SW                 |                                  |
| M2 Select testbeds                     |     SW                 | [2047358-TN-02-2.pdf](2047358/TN-02-2.pdf) |
| D3.1 Performance data                  |     PH                 |                                  |
| D3.2 Portability                       |     PH                 |                                  |
| D3.3 Recommend approach                |     SW                 |                                  |
| M3 Future proofing                     |     SW                 | [2047358-TN-03-2.pdf](2047358/TN-03-2.pdf) |
| D4.1 Report                            |     SW                 |                                  |
| M4 Best practice                       |     SW                 | [2047358-TN-04.pdf](2047358/TN-04.pdf) |
|                                        |                        |                                  |
| **Call 10, 2053622   Kings and Imperial**       |                        |                                  |
| D1.2 2D quad meshes in NekMesh         |     DM                 | [2053622-TN-03-3.pdf](2053622/TN-03-3.pdf) |
| M78-3.1 Proxyapp coordination          |                        | [Nektar-CWIPI](https://github.com/ExCALIBUR-NEPTUNE/nektar-cwipi) |
| **Call 11, 2060042   Imperial and Kings**       |                        |                                  |
| D1.1 Implementation of TensorRegions   |     CC                 | [2060042-TN-01-2.pdf](2060042/TN-01-2.pdf) |
| D3.1 DG performance in Nektar++        |     DM & CC            | [2060042-TN-02-4.pdf](2060042/TN-02-4.pdf) |
|                                        |                        |                                  |
| **Call 12, 2057701   UCL Y3**                   |                        |                                  |
| D1.1 Synthesis of previous outputs     |     SG                 | [2057701-TN-01.pdf](2057701/TN-01.pdf) |
| D3.1/D3.2 SEAVEA toolkit releases      |     PVC/KB             | [2057701-RP-1.pptx](2057701/RP-1.pptx) |
|                                        |                        |                                  |
| **Call 14, 2060049   STFC Y3**                  |                        |                                  |
| D1.1/D2.1 review of timestepping       |     ST & AD            | [2060049-TN-01.pdf](2060049/TN-01.pdf) |
| D3.1 particle-fluid coupling           |     AS                 | [2060049-TN-02.pdf](2060049/TN-02.pdf) |
|                                        |                        |                                  |
| **Call 15, 2068435   Kings**       |                        |                                  |
|                                        |                        |                                  |
| **Call 16, TBD   Oxford**       |                        |                                  |
|                                        |                        |                                  |
| **Call 17, TBD   STFC Y4**                   |                        |                                  |
|                                        |                        |                                  |
| **Call 18, 2067270   York Y4**                  |                        |                                  |
