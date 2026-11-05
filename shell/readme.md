![PROPSTAT Logo in Shell](./example_propstat-logo-shell.png)

# Shell Usage of Propstat Colors and Logo

## Color Scheme 
```
# CI COLORS
PS_DARK_BLUE=$(printf '\033[38;2;0;40;85m')       # #002855
PS_LIGHT_BLUE=$(printf '\033[38;2;94;147;219m')   # #5E93DB
PS_GREY=$(printf '\033[38;2;63;68;68m')           # #3F4444
PS_SKY_BLUE=$(printf '\033[38;2;221;229;237m')    # #DDE5ED

# INTERFACE COLORS
PS_RED=$(printf '\033[38;2;218;41;28m')            # #DA291C
PS_ORANGE=$(printf '\033[38;2;253;170;99m')        # #FDAA63
PS_YELLOW=$(printf '\033[38;2;250;224;83m')        # #FAE053
PS_GREEN=$(printf '\033[38;2;92;170;127m')         # #5CAA7F

# TERMINAL FORMATTING
PS_BOLD=$(printf '\033[1m')
PS_DIM=$(printf '\033[2m')
NC=$(printf '\033[0m')

#=========================================================
# Branding Element and License Declaration
#=========================================================

cat << EOF
=========================================================

            ${PS_DARK_BLUE}${PS_BOLD}ii${PS_LIGHT_BLUE}%%%%%%%             ${PS_DARK_BLUE}i${PS_LIGHT_BLUE}%%%%%%%${NC}           
           ${PS_DARK_BLUE}${PS_BOLD}iiii${PS_LIGHT_BLUE}%%%%%%%           ${PS_DARK_BLUE}iii${PS_LIGHT_BLUE}%%%%%%%${NC}          
          ${PS_DARK_BLUE}${PS_BOLD}iiiiii${PS_LIGHT_BLUE}%%%%%%%         ${PS_DARK_BLUE}iiiii${PS_LIGHT_BLUE}%%%%%%%${NC}         
         ${PS_DARK_BLUE}${PS_BOLD}iiiiiii ${PS_LIGHT_BLUE}%%%%%%%       ${PS_DARK_BLUE}iiiiii ${PS_LIGHT_BLUE}%%%%%%%${NC}        
        ${PS_DARK_BLUE}${PS_BOLD}iiiiiii   ${PS_LIGHT_BLUE}%%%%%%%    ${PS_DARK_BLUE}iiiiiii   ${PS_LIGHT_BLUE}%%%%%%%${NC}       
       ${PS_DARK_BLUE}${PS_BOLD}iiiiiii     ${PS_LIGHT_BLUE}%%%%%%%  ${PS_DARK_BLUE}iiiiiii     ${PS_LIGHT_BLUE}%%%%%%%${NC}      
      ${PS_DARK_BLUE}${PS_BOLD}iiiiiii       ${PS_LIGHT_BLUE}%%%%%%%${PS_DARK_BLUE}iiiiii        ${PS_LIGHT_BLUE}%%%%%%%${NC}     
     ${PS_DARK_BLUE}${PS_BOLD}iiiiiii         ${PS_LIGHT_BLUE}%%%%%%%${PS_DARK_BLUE}iiii          ${PS_LIGHT_BLUE}%%%%%%%${NC}    
    ${PS_DARK_BLUE}${PS_BOLD}iiiiiii           ${PS_LIGHT_BLUE}%%%%%%%${PS_DARK_BLUE}ii            ${PS_LIGHT_BLUE}%%%%%%%${NC}   
   ${PS_DARK_BLUE}${PS_BOLD}iiiiiiiiiiiiiiiiiiii${PS_LIGHT_BLUE}%%%%%%*%%%%%%%%%%%%%%%%%%%%%${NC}  
  ${PS_DARK_BLUE}${PS_BOLD}iiiiiiiiiiiiiiiiiiiiii${PS_LIGHT_BLUE}%%%%%%%%%%%%%%%%%%%%%%%%%%%%${NC}
 ${PS_DARK_BLUE}${PS_BOLD}iiiiiiiiiiiiiiiiiiiiiiii${PS_LIGHT_BLUE}%%%%%%%%%%%%%%%%%%%%%%%%%%%%${NC}
                                                   
${PS_DARK_BLUE}${PS_BOLD}iiiii  iiiiii iiiiii  iiiii  iiiiii iiiiii  iii  iiiiii${NC}
${PS_DARK_BLUE}${PS_BOLD}ii  ii ii  ii ii  ii  ii  ii  ii     ii    ii ii   ii${NC}  
${PS_DARK_BLUE}${PS_BOLD}iiiii  iiiiii ii  ii  iiiii     ii   ii   iiiiiii  ii${NC}  
${PS_DARK_BLUE}${PS_BOLD}ii     ii  ii iiiiii  ii     iiiiii  ii   ii   ii  ii${NC}  

=========================================================
${PS_GREEN}${PS_BOLD}Some Title${NC}
=========================================================
Non-Commercial use is free of charge, please consult our
license for commercial use.
Please use the following link to view the license:
https://github.com/propstat/server-templates?tab=License-1-ov-file
=========================================================
${PS_RED}${PS_BOLD}YOU ARE DOWNLOADING MATERIAL COVERED BY COPYRIGHT AND${NC}
${PS_RED}${PS_BOLD}LICENSED UNDER THE PROPSTAT LICENSE. IF YOU CONTINUE${NC}
${PS_RED}${PS_BOLD}YOU AGREE TO THE LICENSE TERMS.${NC}
=========================================================

EOF
```
