### [IBM i Green Screen](https://www.ibm.com/support/pages/ibm-i-access-client-solutions)

#### Download

Download using the [GitHub .zip download](https://github.com/scottgriv/Dark-Castle-IBMi-Emulator/archive/master.zip) option.

#### Install

1. Open **IBM i Access Client Solutions (ACS)**.  
2. Select **5250 Emulator** from the main window under the **General** section.
3. Load a session or create a new one.
4. From the top menu, go to:  
   **Edit → Preferences → Appearance → Color...**  
5. Click **Import**, then select the included color map file: `Dark-Castle.col`.
6. Click OK or Apply to confirm.

Example of what the `.col` file may contain:

```bash
[ColorRemap]
cRC=12248702
fGN=16766336
fPK=11148166
oSI=4285695
fWT=16744512
oAI=15688819
fTQ=31624
fYW=16766336
mappedType=-936748722493063168
fRD=16711695
BEAN_VERSION=1
sessionType=2
fBL=578080
oEI=16711695
```

*(Set sessionType=1 for display sessions, sessionType=2 for printer sessions if you want both.)*

#### Activate

Once imported:

1. Open your Display Session (or Printer Session) from the Emulator screen.
2. Go to Session → Properties → Appearance → Colors.
3. Choose the imported scheme (e.g., Dark Castle) from the dropdown.
4. Click OK to save.

*Now your IBM i green screen and printer sessions will both use the Dark Castle color scheme — a bold blend of black, amber, and muted neon tones designed to give a modern twist to the classic terminal look.*