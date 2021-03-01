# **APUNTS UF 2.2**

## **OPTIMITZACIÓ**

### **HEDIONDEZ DEL CODI**

- També anomenat **code smell** en anglès.
- Es símptoma en el codi font que indica possiblement un problema més profund.
- Normalment no son **bug** de programació (errors), no son tècnicament incorrectes i en realitat no impedeixen que el programa funcioni correctament.
- Indica deficiències en el disseny que poden alentir el desenvolupament o augmentar el risc d'errors o fallades en el futur.
- Es un motiu important per a realitzar refactorització.

### **ANÀLISIS DEL CODI**

Hi ha de dos tipus:
  - Anàlisis dinàmic (unit tests)
  - Anàlisis estàtic (linit))

#### ANÀLISIS ESTÀTIC DE CODI

L'anàlisi estàtic es realitza mediant analitzadors estàtics (**linters**) o mediant llocs web per a inspecció del codi (**Continuos Inspection**).

Analitzadors estàtics de codi: **lint** (C), **sonar** (Java), **JSLint**, **ESLint** (Javascript)
llocs web d'inspecció de codi (**Continuous Inspection**): **Scrutinizer**, **SonarQube**

### **REFACTORITZACIÓ**

Es el procès de reestructura d'un codi font, alterant la seva estructura interna sense canviar el seu comportament extern.

**TÈCNIQUES:**
  - Canvi de noms de variables
  - Passar codi duplicat a funcions
  - Eliminació de codi inabastable
  - Eliminació de codi redundant
  - Eliminació de codi mort
  - ...

## **DOCUMENTACIÓ**

### **TIPUS DE DOCUMENTACIÓ**

Hi ha tres tipus de documentació:
  - Documentació de codi
  - Documentació tècnica
  - Documentació d'usuari

### **FORMATS DE DOCUMENTACIÓ**

Hi ha quatre tipus de formats de documentació:
  - **HTML** (Javadoc)
  - **Markdown** (Gitbook)
  - **reStrcturedText** ()Readthedocs)
  - **asciiDoc**

### CONTROL DE VERSIONS

Els sistemes més coneguts són:
  - **CVS**
  - **Subversion**
  - **Mercurial**
  - **Git**

### GIT

Les característiques de Git són:
  - Modern
  - Distribuït
  - Eficient

Llocs que suporten Git:
  - **GitHub**
  - **BitBucket**
  - **GitLab**
  - **Coding** (xinès)
