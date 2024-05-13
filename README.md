# Study Files

## meta_study.txt

<table>
    <tr>
        <th>Feld</th>
        <th>Wert</th>
        <th>Kommentar</th>
    </tr>
    <tr>
        <td>type_of_cancer</td>
        <td>mixed</td>
    </tr>
    <tr>
        <td>cancer_study_identifier</td>
        <td>e.g. MTB</td>
        <td>Über alle Meta-Files einer Study hinweg gleich</td>
    </tr>
    <tr>
        <td>name</td>
        <td>e.g. Molekulares Tumorboard Erlangen</td>
    </tr>
    <tr>
        <td>description</td>
        <td>e.g. Molekulares Tumorboard Erlangen</td>
    </tr>
    <tr>
        <td>groups</td>
        <td>e.g. MTB</td>
        <td>Legt Sichtbarkeit für Keycloak User fest</td>
    </tr>
</table>

## meta_muations_extended.txt

<table>
    <tr>
        <th>Feld</th>
        <th>Wert</th>
        <th>Kommentar</th>
    </tr>
    <tr>
        <td>cancer_study_identifier</td>
        <td>e.g. MTB</td>
    </tr>
    <tr>
        <td>genetic_alteration_type</td>
        <td>MUTATION_EXTENDED</td>
        <td></td>
    </tr>
    <tr>
        <td>datatype</td>
        <td>MAF</td>
        <td></td>
    </tr>
    <tr>
        <td>stable_id</td>
        <td>mutations</td>
        <td></td>
    </tr>
    <tr>
        <td>show_profile_in_analysis_tab</td>
        <td>true</td>
        <td></td>
    </tr>
    <tr>
        <td>profile_name</td>
        <td>e.g. Mutations</td>
        <td></td>
    </tr>
    <tr>
        <td>profile_description</td>
        <td>e.g. Mutation data from TSO500</td>
        <td></td>
    </tr>
    <tr>
        <td>data_filename</td>
        <td>data_mutations_extended.txt</td>
        <td></td>
    </tr>
    <tr>
        <td>namesspaces</td>
        <td>e.g. MTB</td>
        <td>weitere Spalten können der MAF mit "Namespace.Spaltenname" hinzugefügt werden, hier z.B. "MTB.Klassifikation"</td>
    </tr>
</table>

## data_muations_extended.txt (MAF-Datei)

<table>
    <tr>
        <td>Hugo_Symbol</td>
        <td>Entrez_Gene_Id</td>
        <td>NCBI_Build</td>
        <td>Chromosome</td>
        <td>Start_Position</td>
        <td>End_Position</td>
        <td>Strand</td>
        <td>Variant_Classification</td>
        <td>Variant_Type</td>
        <td>Reference_Allele</td>
        <td>Tumor_Seq_Allele1</td>
        <td>Tumor_Seq_Allele2</td>
        <td>dbSNP_RS</td>
        <td>Tumor_Sample_Barcode</td>
        <td>Match_Norm_Seq_Allele1</td>
        <td>Match_Norm_Seq_Allele2</td>
        <td>HGVSc</td>
        <td>HGVSp</td>
        <td>HGVSp_Short</td>
        <td>Transcript_ID</td>
        <td>Exon_Number</td>
        <td>t_depth</td>
        <td>t_ref_count</td>
        <td>t_alt_count</td>
        <td>all_effects</td>
        <td>Allele</td>
        <td>Gene</td>
        <td>Feature</td>
        <td>Feature_type</td>
        <td>Consequence</td>
        <td>cDNA_position</td>
        <td>CDS_position</td>
        <td>Protein_position</td>
        <td>Amino_acids</td>
        <td>Codons</td>
        <td>Existing_variation</td>
        <td>DISTANCE</td>
        <td>STRAND_VEP</td>
        <td>SYMBOL</td>
        <td>SYMBOL_SOURCE</td>
        <td>BIOTYPE</td>
        <td>CANONICAL</td>
        <td>EXON</td>
        <td>INTRON</td>
        <td>AF</td>
        <td>AFR_AF</td>
        <td>AMR_AF</td>
        <td>EAS_AF</td>
        <td>EUR_AF</td>
        <td>SAS_AF</td>
        <td>CLIN_SIG</td>
        <td>SOMATIC</td>
        <td>PUBMED</td>
        <td>IMPACT</td>
        <td>PHENO</td>
        <td>FILTER</td>
        <td>flanking_bps</td>
        <td>vcf_qual</td>
        <td>gnomAD_AF</td>
        <td>gnomAD_AFR_AF</td>
        <td>gnomAD_AMR_AF</td>
        <td>gnomAD_ASJ_AF</td>
        <td>gnomAD_EAS_AF</td>
        <td>gnomAD_FIN_AF</td>
        <td>gnomAD_NFE_AF</td>
        <td>gnomAD_OTH_AF</td>
        <td>gnomAD_SAS_AF</td>
        <td>vcf_pos</td>
        <td>t_VF</td>
        <td>MTB.Klassifikation</td>
    </tr>
</table>

## meta_sv_fusions.txt

Noch in Arbeit

## data_sv_fusions.txt

Noch in Arbeit

## meta_clinical_sample.txt

<table>
    <tr>
        <th>Feld</th>
        <th>Wert</th>
        <th>Kommentar</th>
    </tr>
    <tr>
        <td>cancer_study_identifier</td>
        <td>e.g. MTB</td>
        <td>Über alle Meta-Files einer Study hinweg gleich</td>
    </tr>
    <tr>
        <td>genetic_alteration_type</td>
        <td>CLINICAL</td>
    </tr>
    <tr>
        <td>datatype</td>
        <td>SAMPLE_ATTRIBUTES</td>
    </tr>
    <tr>
        <td>data_filename</td>
        <td>data_clinical_sample.txt</td>
    </tr>
</table>

## data_clinical_sample.txt

    Row 1: The attribute Display Names
    Row 2: The attribute Descriptions
    Row 3: The attribute Datatype
    Row 4: The attribute Priority
    Row 5: The attribute name for the database
    Row 6: data

<table>
    <tr>
        <td>#Patient Identifier</td>
        <td>Sample Identifier</td>
        <td>Sequenzierung DNA Panel</td>
        <td>TMB Score</td>
        <td>MSI</td>
        <td>DATE</td>
    </tr>
    <tr>
        <td>#Patient Identifier</td>
        <td>Sample Identifier</td>
        <td>Sequenzierung DNA Panel</td>
        <td>TMB Score</td>
        <td>MSI</td>
        <td>DATE</td>
    </tr>
    <tr>
        <td>#STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
    </tr>
    <tr>
        <td>#1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
    </tr>
    <tr>
        <td>PATIENT_ID</td>
        <td>SAMPLE_ID</td>
        <td>SEQUENCING_DNA_PANEL</td>
        <td>TMB_SCORE</td>
        <td>MSI</td>
        <td>DATE</td>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 12345678-1234567890</td>
        <td>e.g. TruSight Oncology 500</td>
        <td>e.g. 5.0</td>
        <td>e.g. 0.85</td>
        <td>e.g. 2023-01-01</td>
    </tr>
        <tr>
        <td>Pflichtfeld</td>
        <td>Pflichtfeld</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## meta_clinical_patient.txt

<table>
    <tr>
        <th>Feld</th>
        <th>Wert</th>
        <th>Kommentar</th>
    </tr>
    <tr>
        <td>cancer_study_identifier</td>
        <td>e.g. MTB</td>
        <td></td>
    </tr>
    <tr>
        <td>genetic_alteration_type</td>
        <td>CLINICAL</td>
        <td></td>
    </tr>
    <tr>
        <td>datatype</td>
        <td>PATIENT_ATTRIBUTES</td>
        <td></td>
    </tr>
    <tr>
        <td>data_filename</td>
        <td>data_clinical_patient.txt</td>
        <td></td>
    </tr>
</table>

## data_clinical_patient.txt

    Row 1: The attribute Display Names
    Row 2: The attribute Descriptions
    Row 3: The attribute Datatype
    Row 4: The attribute Priority
    Row 5: The attribute name for the database
    Row 6: data

<table>
    <tr>
        <td>#Patient Identifier</td>
        <td>Birthdate</td>
        <td>Sex</td>
        <td>Death</td>
        <td>Overall survival status</td>
        <td>Diagnosis date</td>
        <td>Age when diagnosed</td>
        <td>ICD10 Code</td>
        <td>Diagnosis</td>
        <td>ICD-O3-Localisation</td>
        <td>ICD-O3-Histology</td>
        <td>MTB registration date</td>
        <td>Guideline status</td>
        <td>Distant metastases</td>
        <td>Response to last therapy line</td>
        <td>Tumor site</td>
    </tr>
    <tr>
        <td>#Patient Identifier</td>
        <td>Birthdate</td>
        <td>Sex</td>
        <td>Date of death</td>
        <td>Overall patient survival status</td>
        <td>Date of diagnosis</td>
        <td>Age at which a condition or disease was first diagnosed</td>
        <td>ICD10 Code</td>
        <td>Diagnosis</td>
        <td>ICD-O3-Localisation</td>
        <td>ICD-O3-Histology</td>
        <td>MTB registration date</td>
        <td>Leitlinienstatus Description</td>
        <td>Distant metastases (spread of disease)</td>
        <td>Response to last therapy line</td>
        <td>Tumor site</td>
    </tr>
    <tr>
        <td>#STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>NUMBER</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
        <td>STRING</td>
    </tr>
    <tr>
        <td>#1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
    </tr>
    <tr>
        <td>PATIENT_ID</td>
        <td>BIRTHDATE</td>
        <td>SEX</td>
        <td>DEATH_DATE</td>
        <td>OS_STATUS</td>
        <td>DIAGNOSIS_DATE</td>
        <td>AGE</td>
        <td>ICD_10_CODE</td>
        <td>DIAGNOSIS</td>
        <td>ICD_03_LOCALISATION</td>
        <td>ICD_03_Histology</td>
        <td>DATE_MTB_REGISTRATION</td>
        <td>GUIDELINE_STATUS_DESC</td>
        <td>DISTANT_METASTASES</td>
        <td>RESPONSE</td>
        <td>TUMOR_SITE</td>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 2000-01-01</td>
        <td>e.g. w</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
        <tr>
        <td>Pflichtfeld</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## dates_first_diagnosis.txt

<table>
    <tr>
        <td>PATIENT_ID</td>
        <td>DATE</td>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 2024-01-01</td>
    </tr>
</table>

## meta_timeline.txt

<table>
    <tr>
        <th>Feld</th>
        <th>Wert</th>
        <th>Kommentar</th>
    </tr>
    <tr>
        <td>cancer_study_identifier</td>
        <td>e.g. MTB</td>
    </tr>
    <tr>
        <td>genetic_alteration_type</td>
        <td>CLINICAL</td>
        <td></td>
    </tr>
    <tr>
        <td>datatype</td>
        <td>TIMELINE</td>
        <td></td>
    </tr>
    <tr>
        <td>data_filename</td>
        <td>data_timeline_XXX.txt</td>
        <td>unterschiedlich, je nach Timeline-Event</td>
    </tr>
</table>

## data_timeline_biopsy.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>SAMPLE</th>
        <th>DATE</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td></td>
        <td>BIOPSY</td>
        <td>#0000ff</td>
        <td>e.g. Fernmetastase</td>
        <td>e.g. 2023-01-01</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## data_timeline_ecog.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>ECOG</th>
        <th>DISEASE</th>
        <th>DATE</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td></td>
        <td>ECOG</td>
        <td>#0000ff</td>
        <td>e.g. 1</td>
        <td>e.g. Bösartige Neubildung der Schilddrüse</td>
        <td>e.g. 2023-01-01</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## data_timeline_labtest.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>TEST</th>
        <th>RESULT</th>
        <th>UNIT</th>
        <th>DATE</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td></td>
        <td>LAB_TEST</td>
        <td>#0000ff</td>
        <td>e.g. PSA</td>
        <td>e.g. 5,66</td>
        <td>e.g. ng/ml</td>
        <td>e.g. 2023-01-01</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## data_timeline_spread.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>DESCRIPTION</th>
        <th>DISEASE</th>
        <th>DATE</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td></td>
        <td>SPREAD OF DISEASE</td>
        <td>#0000ff</td>
        <td>e.g. Metastasiert</td>
        <td>e.g. Bösartige Neubildung der Schilddrüse</td>
        <td>e.g. 2023-01-01</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## data_timeline_staging.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>TNM_ORG</th>
        <th>CTNM</th>
        <th>DTNM</th>
        <th>GESAMT_R</th>
        <th>STADIUM</th>
        <th>FIGO_STADIUM</th>
        <th>GLEASON_SCORE</th>
        <th>ANN_ARBOR</th>
        <th>DISEASE</th>
        <th>DATE</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td></td>
        <td>STAGING</td>
        <td>#0000ff</td>
        <td>e.g. UICC</td>
        <td>e.g. cM1</td>
        <td>e.g. cM1</td>
        <td>e.g. R0</td>
        <td>e.g. IV</td>
        <td></td>
        <td>e.g. 7b</td>
        <td></td>
        <td>e.g. Bösartige Neubildung der Schilddrüse</td>
        <td>e.g. 2023-01-01</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## data_timeline_surgery.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>STATUS</th>
        <th>INTENTION</th>
        <th>TUMOR_SECTION</th>
        <th>METASTASIS_RESECTION</th>
        <th>METASTASIS_LOCATION</th>
        <th>R_CLASSIFICATION</th>
        <th>R_DEFINITELY</th>
        <th>NOTE</th>
        <th>DISEASE</th>
        <th>DATE</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td>e.g. 120</td>
        <td>SURGERY</td>
        <td>#0000ff</td>
        <td>e.g. durchgeführt</td>
        <td>e.g. Diagnostisch</td>
        <td>e.g. Nein</td>
        <td>e.g. Ja</td>
        <td>e.g. Knochen</td>
        <td>e.g. RX</td>
        <td>e.g. 1</td>
        <td>e.g. Teilresektion</td>
        <td>e.g. Bösartige Neubildung der Schilddrüse</td>
        <td>e.g. 2023-01-01</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## data_timeline_tumorboard.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>TUMORBOARD</th>
        <th>TYPE</th>
        <th>QUESTION</th>
        <th>RECOMMENDATION</th>
        <th>NOTE</th>
        <th>DATE</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td>e.g. 120</td>
        <td>TUMORBOARD</td>
        <td>#0000ff</td>
        <td>e.g. TB Molekulares Tumorboard</td>
        <td>e.g. Prätherapeutisch</td>
        <td></td>
        <td></td>
        <td></td>
        <td>e.g. 2023-01-01</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

## data_timeline_treatment_medical.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>TREATMENT_TYPE</th>
        <th>SUBTYPE</th>
        <th>AGENT</th>
        <th>AGENT_CLASS</th>
        <th>SUBSTANCE_ATC</th>
        <th>ENDING_STATUS</th>
        <th>RESULT</th>
        <th>REASON_FOR_TERMINATION</th>
        <th>STARTED</th>
        <th>ENDED</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td>e.g. 120</td>
        <td>TREATMENT</td>
        <td>#0000ff</td>
        <td>Medical Therapy</td>
        <td>e.g. Chemotherapie, Immuntherapie</td>
        <td>e.g. Docetaxel</td>
        <td></td>
        <td>e.g. L02AE02</td>
        <td>e.g. Reguläres Ende</td>
        <td>e.g. Progression</td>
        <td>e.g. Progression</td>
        <td>e.g. 2023-01-01</td>
        <td>e.g. 2023-01-02</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>


## data_timeline_treatment_radiation.txt

<table>
    <tr>
        <th>PATIENT_ID</th>
        <th>START_DATE</th>
        <th>STOP_DATE</th>
        <th>EVENT_TYPE</th>
        <th>STYLE_COLOR</th>
        <th>TREATMENT_TYPE</th>
        <th>SUBTYPE</th>
        <th>ENDING_STATUS</th>
        <th>STATUS</th>
        <th>STARTED</th>
        <th>ENDED</th>
    </tr>
    <tr>
        <td>e.g. 1234567890</td>
        <td>e.g. 0</td>
        <td>e.g. 120</td>
        <td>TREATMENT</td>
        <td>#0000ff</td>
        <td>Radiation Therapy</td>
        <td>e.g. Radio-/Chemotherapie </td>
        <td>e.g. Reguläres Ende</td>
        <td>e.g. durchgeführt</td>
        <td>e.g. 2023-01-01</td>
        <td>e.g. 2023-01-02</td>
    </tr>
    <tr>
        <td>Pflichtspalte; <br> Tage seit der Erstdiagnose</td>
        <td>Pflichtspalte; <br> Bei Zeitpunkt-Events leer</td>
        <td>Pflichtspalte</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>


# Eingebettete Ressourcen

in Arbeit (Präsentationen, Bilder, etc..)

