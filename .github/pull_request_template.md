# References

<!-- Una línea por cada URL de las tareas y los pulls requests relacionados a este pull request ya sea porque sean pull request en subrepositorios o pulls de repositorios "padre" -->

<!-- Procedimiento para Crear Pull Request: -->

<!-- https://documentation.embention.net/063/es/latest/index.html  -->

# Changelog

<!-- Items del changelog públicos -->

* Added:

  <!--  - Description of content added 1 -->

  <!--  - Description of content added 2 -->
* Removed:

  <!--  - Description of content removed 1 -->

  <!--  - Description of content removed 2 -->
* Changed:

  <!--  - Description of content changed 1 -->

  <!--  - Description of content changed 2 -->
* Fixed:

  <!--  - Description of content fixed 1 -->

  <!--  - Description of content fixed 2 -->

<!-- Items del changelog privados -->

> * Added:

<!-- >>* Description of content added 1 -->

<!-- >>* Description of content added 2 -->

> * Removed:

<!-- >>* Description of content removed 1 -->

<!-- >>* Description of content removed 2 -->

> * Changed:

<!-- >>* Description of content changed 1 -->

<!-- >>* Description of content changed 2 -->

> * Fixed:

<!-- >>* Description of content fixed 1 -->

<!-- >>* Description of content fixed 2 -->

# Description

<!-- Describir con el fin de evitar preguntas las acciones realizadas, problemas encontrados, configuración necesaria, pruebas realizadas, etc... -->

<!-- Pull request created to review the artifacts shown in the files changed section. The following inputs and/or the linked Github Issue/Problem Report in the reference section are needed for the review process:  -->

<!-- Optional: for changes limited to non-airborne process configuration files, copy the text below into Description only after confirming that every statement applies. Otherwise remove this comment.

Updates to non-airborne process configuration files.

The files modified are identified as non-airborne/non-executable process artifacts. These modifications:
- Do not impact the integrity or content of the Executable Object Code (EOC) or Parameter Data Item (PDI).
- Do not require changes to the controlled software/hardware requirements base.
-->

# Affected Items

<!-- Check the software items and applications affected by this change -->
## Affected Software Items
<!-- Init software items -->
- [ ] sw_1xVeronte
- [ ] sw_1x_bootloader
- [ ] sw_SIL
- [ ] sw_Remote_ID
- [ ] sw_kai
- [ ] sw_veronte_kai
- [ ] sw_VML
- [ ] sw_Astro
- [ ] sw_PA_SIL
- [ ] sw_vbootloader_astro
- [ ] sw_IPC
- [ ] sw_IPC_SIL
- [ ] sw_vbootloader_ipc
- [ ] sw_MC110
- [ ] sw_MC110-vbootloader
- [ ] sw_MCx
- [ ] sw_MCx-bootloader
- [ ] sw_Remote_ID
- [ ] sw_CEX
- [ ] sw_CEX_SIL
- [ ] sw_MEX
- [ ] sw_REx
- [ ] sw_REx_SIL
- [ ] sw_ACEX
- [ ] sw_RadarDAA
- [ ] sw_daa
- [ ] sw_ai_detection
- [ ] sw_STK
- [ ] sw_STK_bootloader
- [ ] sw_bootloader_rex
- [ ] sw_bootloader_kai
- [ ] sw_servo
- [ ] sw_servo_bootloader
- [ ] sw_MC01
- [ ] sw_V_HALO
- [ ] sw_bootloader_ACEX
- [ ] sw_ACEX
- [ ] sw_Arbiter
<!-- End software items -->

## Affected Apps
<!-- Init affected apps -->
**PDI Builders**
- [ ] sw_1x-pdi-builder
- [ ] sw_cex-pdi-builder
- [ ] sw_kai-pdi-builder
- [ ] sw_REx-pdi-builder
- [ ] sw_mex-pdi-builder
- [ ] sw_mc110-pdi-builder
- [ ] sw_nex-pdi-builder
- [ ] sw_mcx-pdi-builder
- [ ] sw_inc-pdi-builder
- [ ] sw_v-pnt-pdi-builder
- [ ] sw_veronte-pdi-builder

**PDI Tuning**
- [ ] sw_1x-pdi-tuning
- [ ] sw_pdi-tuning

**PDI Calibration**
- [ ] sw_1x-pdi-calibration
- [ ] sw_pdi-installation


**Apps & CLI Tools**
- [ ] sw_udp-telemetry-cli
- [ ] sw_vsa
- [ ] sw_postflight-cli
- [ ] sw_hil
- [ ] sw_VeronteOps
- [ ] sw_VeronteLink
- [ ] sw_VeronteFDR
- [ ] sw_veronte-updater
- [ ] sw_VeronteTerrainProvider
- [ ] sw_CITEC
- [ ] sw_stec
- [ ] sw_ate_trainer
<!-- End affected apps -->

# Checklist

<details>
<summary>Checklist Summary</summary>

Software Development Process DO-178C
- [P.413-planning-process-verification-activity-checklist](https://documentation.embention.net/413/en/latest/index.html)
- [P.414-requirement-verification-activity-checklist](https://documentation.embention.net/414/en/latest/index.html)
- [P.415-design-verification-activity-checklist](https://documentation.embention.net/415/en/latest/index.html)
- [P.416-code-verification-activity-checklist](https://documentation.embention.net/416/en/latest/index.html)
- [P.417-integration-verification-activity-checklist](https://documentation.embention.net/417/en/latest/index.html)
- [P.418-test-cases-activity-checklist](https://documentation.embention.net/418/en/latest/index.html)
- [P.419-test-results-activity-checklist](https://documentation.embention.net/419/en/latest/index.html)
- [P.695-software-change-impact-analysis-checklist](https://documentation.embention.net/695/en/latest/index.html)

Software Document Development DO-178C
- [P.748-software-requirements-data-activity-checklist-srd](https://documentation.embention.net/748/en/latest/index.html)
- [P.749-software-design-data-activity-checklist-sdd](https://documentation.embention.net/749/en/latest/index.html)
- [P.750-software-configuration-index-activity-checklist-sci](https://documentation.embention.net/750/en/latest/index.html)
- [P.751-software-verification-records-activity-checklist-svr](https://documentation.embention.net/751/en/latest/index.html)
- [P.752-software-trade-data-activity-checklist-td](https://documentation.embention.net/752/en/latest/index.html)
- [P.757-software-life-cycle-environment-configuration-index-checklist-seci](https://documentation.embention.net/757/en/latest/index.html)
- [P.758-software-accomplishment-summary-checklist-sas](https://documentation.embention.net/758/en/latest/index.html)
- [P.759-software-verification-cases-and-procedures-checklist-svcp](https://documentation.embention.net/759/en/latest/index.html)

Software Quality Assurance Process DO-178C
- [P.420-sqap-checklist](https://documentation.embention.net/420/en/latest/index.html)
- [P.691-test-readiness-review-checklist-trr](https://documentation.embention.net/691/en/latest/index.html)
- [P.693-software-conformity-review-checklist-scr](https://documentation.embention.net/693/es/latest/index.html)
- [P.740-sqap-peer-review-checklist](https://documentation.embention.net/740/en/latest/index.html)
- [P.741-sqap-integration-review-checklist](https://documentation.embention.net/741/en/latest/index.html)
- [P.742-sqap-configuration-management-checklist](https://documentation.embention.net/742/en/latest/index.html)
- [P.743-sqap-test-execution-review-checklist](https://documentation.embention.net/743/en/latest/index.html)

PDI Development Process DO-178C
- [P.438-pdi-design-verification-activity-checklist](https://documentation.embention.net/438/en/latest/index.html)
- [P.617-pdi-requirement-verification-activity-checklist](https://documentation.embention.net/617/en/latest/index.html)
- [P.763-pdi-file-verification-activity-checklist](https://documentation.embention.net/763/en/latest/index.html)
- [P.764-pdi-xml-intermediate-representation-verification-activity-checklist](https://documentation.embention.net/764/en/latest/index.html)
- [P.766-pdi-configuration-index-review-checklist-pdici](https://documentation.embention.net/766/en/latest/index.html)
- [P.809-pdi-environment-life-cycle-configuration-index-review-checklist-pdieci](https://documentation.embention.net/809/en/latest/index.html)

Tool Development Process DO-330
- [P.692-sqap-software-tool-life-cycle-data-checklist](https://documentation.embention.net/692/en/latest/index.html)
- [P.745-sqap-software-tool-user-data-checklist](https://documentation.embention.net/745/en/latest/index.html)
- [P.746-sqap-software-tool-developer-data-checklist](https://documentation.embention.net/746/en/latest/index.html)
- [P.747-sqap-software-tool-conformity-review-checklist](https://documentation.embention.net/747/en/latest/index.html)

Hardware Development Process DO-254
- [P.545-hardware-requirement-verification-checklist](https://documentation.embention.net/545/en/latest/index.html)
- [P.673-hardware-verification-wi-checklist](https://documentation.embention.net/673/en/latest/index.html)
- [P.674-hardware-verification-tr-checklist](https://documentation.embention.net/674/en/latest/index.html)
- [P.726-Hardware-change-impact-analysis-checklist](https://documentation.embention.net/726/en/latest/index.html)
- [P.832-Hardware-Planning-Process-Verification-Activity-Checklist](https://documentation.embention.net/832/en/latest/index.html)
- [P.856-review-and-analysis-results-checklist](https://documentation.embention.net/856/en/latest/index.html)
- [P.857-block-diagram-development-checklist](https://documentation.embention.net/857/en/latest/index.html)
- [P.931-Hardware-Validation-Activity-Checklist](https://documentation.embention.net/931/en/latest/index.html)

Hardware Document Development DO-254
- [P.833-hardware-design-description-checklist-hdd](https://documentation.embention.net/833/en/latest/index.html)
- [P.834-hardware-requirement-data-checklist-hrd](https://documentation.embention.net/834/en/latest/index.html)
- [P.835-hardware-configuration-index-checklist-hci](https://documentation.embention.net/835/en/latest/index.html)
- [P.838-hardware-accomplishment-summary-checklist-has](https://documentation.embention.net/838/en/latest/index.html)
- [P.903-Hardware-Trace-Data-Checklist-HTD](https://documentation.embention.net/903/en/latest/index.html)

Hardware Process Assurance Process DO-254
- [P.732-hardware-conformity-review-checklist-hcr](https://documentation.embention.net/732/en/latest/index.html)
- [P.733-hardware-test-readiness-review-checklist-htrr](https://documentation.embention.net/733/en/latest/index.html)
- [P.874-HPAP-Planning-Documents-Checklist](https://documentation.embention.net/874/en/latest/index.html)
- [P.936-HPAP---Peer-Review-Checklist](https://documentation.embention.net/936/en/latest/index.html)

Environmental Qualification DO-160
- [P.906-Environmental-Qualification-Plan-Checklist](https://documentation.embention.net/906/en/latest/index.html)
- [P.907-Environmental-Test-Procedures-Checklist](https://documentation.embention.net/907/en/latest/index.html)
- [P.908-Environmental-Qualification-Report-Checklist](https://documentation.embention.net/908/en/latest/index.html)
- [P.913-Environmental-Verification-Activity-Checklist](https://documentation.embention.net/913/en/latest/index.html)

System Development Process ARP4754B - ED79B
- [P.406 - Definición y composición de sistema o producto: Aprobación y commiteo en Git](https://documentation.embention.net/406/es/010/index.md#aprobacion-y-commiteo-en-git)
- [P.875-assurance](https://documentation.embention.net/875/en/latest/index.html)
- [P.876-System-Development-Process-and-Requirements-Capture-checklist](https://documentation.embention.net/876/en/latest/index.html)
- [P.878-Requirements-Validation-Process-checklist](https://documentation.embention.net/878/en/latest/index.html)
- [P.879-Implementation-Verification-Process-checklist](https://documentation.embention.net/879/en/latest/index.html)
- [P.880-Configuration-Management-Process-checklist](https://documentation.embention.net/880/en/latest/index.html)
- [P.881-Process-Assurance-Process-Checklist](https://documentation.embention.net/881/en/latest/index.html)

Safety Development Process ARP4761 - ED135
- [P.877-Safety-Assessment-Process-checklist](https://documentation.embention.net/877/en/latest/index.html)

3d Process Development
- [P.079-revision-y-aprobacion-de-disenos-mecanicos](https://documentation.embention.net/079/en/latest/index.html)

Manuales y Procedimientos
- [P.754-procedure-verification-activity-checklist](https://documentation.embention.net/754/en/latest/index.html)
- [P.735-user-manual-verification-activity-checklist](https://documentation.embention.net/735/en/latest/index.html)

</details>
