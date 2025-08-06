# abapgit-PDFsnaphot_transactions
View/Print snapshot of any SAP transactions in PDF format.

Please extract the ZIP file $PRABHA_20250806_154224.zip. This file contains the following objects.

(1) ABAP Report zpdf_viewer

(2) Database tables zfp_it_m_key and zfp_pdf_form

(3) Maintenance View zfp_forms_mv, which links the primary table zfp_it_m_key and secondary table zfp_pdf_form

(4) Function Group zprabha and the Function Module zgenerate_pdf_xstring

(5) Search Help zfp_it_m_key

Create data in the tables zfp_it_m_key and zfp_pdf_form.

Sample data for the table zfp_it_m_key, Please add the needed Application Object Types (e.g. BILLING_DOCUMENT, PURCHASE_ORDER, ..etc in this table) for which you want to View/Print the transaction data in the PDF fromat.

<img width="416" height="465" alt="image" src="https://github.com/user-attachments/assets/5ec4e7bc-103c-464e-b2da-fe0defb7ae4c" />

<img width="397" height="385" alt="image" src="https://github.com/user-attachments/assets/f7f51b70-0951-4413-bab7-b5e4ecaca406" />

<img width="412" height="388" alt="image" src="https://github.com/user-attachments/assets/08eceba6-0722-4dc1-819b-0ef837f7d79d" />

Application Object Types (e.g. BILLING_DOCUMENT, PURCHASE_ORDER, ..etc)  are provided on the table APOC_I_OBJ_TYPE


Sample data for the table zfp_pdf_form

<img width="426" height="207" alt="image" src="https://github.com/user-attachments/assets/9b78d2c5-fef9-4b83-b1d9-98e3065fc43e" />

<img width="438" height="157" alt="image" src="https://github.com/user-attachments/assets/e5563755-6ee9-4fc9-9d6c-2c3523a30e06" />

Adobe Master template APOC_DEMO_FORM_MASTER_CA and Content template MM_PUR_PURCHASE_ORDER are standard SAP ADOBE templates. But you can also replace them with your own custom templates

Now you can execute the report zpdf_viewer or tcode ZPDF_VIEWER

<img width="933" height="472" alt="image" src="https://github.com/user-attachments/assets/8820dcb9-c5d7-4c05-96fd-e151ecb3660a" />

Results - You will be able to Preview/Print the snapshot of you transaction data in PDF Format

<img width="1044" height="277" alt="image" src="https://github.com/user-attachments/assets/38d20b4e-b1a3-440e-b2b4-52e0416a2d76" />




 
