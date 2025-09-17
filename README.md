<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Layout</title>
</head>
<body style="padding: 20px; font-family: Arial, sans-serif; background-color: #f6f8fa;">
    <div style="display: flex; align-items: flex-start; gap: 30px; max-width: 1200px;">
        <!-- Colonne gauche : Logos des compétences alignés verticalement -->
        <div style="display: flex; flex-direction: column; gap: 15px; align-items: center;">
            <a href="https://en.wikipedia.org/wiki/C_(programming_language)" target="_blank">
                <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/C.svg" width="48" alt="C" style="transition: transform 0.2s; border-radius: 8px;" />
            </a>
            <a href="https://en.wikipedia.org/wiki/Bash_(Unix_shell)" target="_blank">
                <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/65dea6c4eaca7da319e552c09f4cf5a9a8dab2c8/icons/Bash-Dark.svg" width="48" alt="Bash" style="transition: transform 0.2s; border-radius: 8px;" />
            </a>
            <a href="https://en.wikipedia.org/wiki/Vim_(text_editor)" target="_blank">
                <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/NeoVim-Dark.svg" width="48" alt="NeoVim" style="transition: transform 0.2s; border-radius: 8px;" />
            </a>
            <a href="https://en.wikipedia.org/wiki/List_of_Linux_distributions" target="_blank">
                <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/Linux-Dark.svg" width="48" alt="Linux" style="transition: transform 0.2s; border-radius: 8px;" />
            </a>
            <a href="https://en.wikipedia.org/wiki/Git" target="_blank">
                <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/Git.svg" width="48" alt="Git" style="transition: transform 0.2s; border-radius: 8px;" />
            </a>
        </div>
        
        <!-- Colonne droite : Stats et logo -->
        <div style="display: flex; flex-direction: column; gap: 25px; flex: 1;">
            <!-- Stats LeetCode -->
            <div style="text-align: center;">
                <img src="https://leetcard.jacoblin.cool/sdemey00?theme=wtf" 
                     width="100%" 
                     style="max-width: 500px; border-radius: 12px; box-shadow: 0px 4px 15px rgba(0,0,0,0.15); transition: transform 0.2s;" 
                     alt="LeetCode Stats" 
                     onmouseover="this.style.transform='scale(1.02)'" 
                     onmouseout="this.style.transform='scale(1)'" />
            </div>
            
            <!-- Logo Campus 19 -->
            <div style="text-align: center;">
                <img src="https://land.campus19.be/wp-content/uploads/2024/08/cropped-Design-sans-titre-26.png" 
                     alt="Campus 19 Logo" 
                     width="180" 
                     style="border-radius: 12px; box-shadow: 0px 4px 15px rgba(0,0,0,0.15); transition: transform 0.2s;" 
                     onmouseover="this.style.transform='scale(1.05)'" 
                     onmouseout="this.style.transform='scale(1)'" />
            </div>
        </div>
    </div>

    <style>
        /* Effet hover sur les icônes de compétences */
        a img:hover {
            transform: scale(1.1) !important;
        }
        
        /* Responsive design */
        @media (max-width: 768px) {
            body > div {
                flex-direction: column;
                align-items: center;
                gap: 20px;
            }
            
            body > div > div:first-child {
                flex-direction: row;
                gap: 20px;
            }
        }
    </style>
</body>
</html>
