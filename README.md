# SAP_ECC_ME51N_F4_SEARCH_HELP
Add F4-Search Help ME51N

[Tutorial] Add F4-Search Help Requisitioner and Tracking in ME51N (Create PR)
by: John Eswin Nizar

Video : https://youtu.be/o_3Gtbw191k

1. Create Z Table for Requisitioner
   ZMMT_REQUISNR1

2. Create Z Table for Tracking
   ZMMT_TRACKING1

3. Create Search Help for Requisitioner
   ZSH_AFNAM

4. Create Search Help for Tracking
   ZSH_BEDNR

5. Modify Structure MEREQ3328
   Click Change -> Access Key Required -> If Accepted -> Maint. in Logon Language
   Select field AFNAM / BEDNR

6. Enhancement Program LMEGUICJM
   1. Click Enhancement 
   2. Go To Menu : Edit -> Enhancement Operations -> Show Implicit Enhancement Options
   3. Paste Script between ENHANCEMENT

7. Test
   1. ME51N -> Click Requisitioner -> Press F4
      ME51N -> Click Tracking -> Press F4
   2. Function Person List


