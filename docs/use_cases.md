# Розроблення функціональних вимог до системи

## Модель прецедентів

### 1. Діаграма UserRegister
[![Діаграма UserRegister](https://img.plantuml.biz/plantuml/svg/ZPFDIiD04CVlWRp3q8jwQ1z0Igb81QzARmK9oIg1D9LD8lNM3z1R2r8g258V8KWhiJNr5MRVoDbDqoQjHNFPPMV-l_bCrVCDxWTD1-eUunVinlPyndLDrmpJRt705roA3aQYAtgYZ-yOYaSmFEKjlGAFcOR7e7vwbOf1VUHJo28RBhxXJ8mKg4EO1p4MGy3vBX_3GWvyoLohrZHiPmt6LmnnIe0kBaZHmmZeeY20ts9CjXwnPaIUuWVECCPO3FFKqvPxRVCcvRUcJhQKaIBJTJllGHvrud1cMFUrDbNg9QZVsaO7vG8gxLZqnQZX7ieMvUIrjibkVRlb7kLZdBjtXcEdVLWrORPg7vsKQemHVWAJ7aJE2lP1pyZ6B83Do722I_mYq8BG8SZyAUqaXceYKEV9GaN5iZGAb4oO6vAV07FXT4tM24LUh6It97qEakVDDCYGsQLKbjs1OoYNRTTq0ejLAiezCylITY3bpje-0QIthXq0Fb61Sro80IrRBCPKffmrrPICzrb1yrCjfPdkuUwCw1-2VFl_4kXQbMxqg_u0)](https://editor.plantuml.com/uml/ZPFDIiD04CVlWRp3q8jwQ1z0Igb81QzARmK9oIg1D9LD8lNM3z1R2r8g258V8KWhiJNr5MRVoDbDqoQjHNFPPMV-l_bCrVCDxWTD1-eUunVinlPyndLDrmpJRt705roA3aQYAtgYZ-yOYaSmFEKjlGAFcOR7e7vwbOf1VUHJo28RBhxXJ8mKg4EO1p4MGy3vBX_3GWvyoLohrZHiPmt6LmnnIe0kBaZHmmZeeY20ts9CjXwnPaIUuWVECCPO3FFKqvPxRVCcvRUcJhQKaIBJTJllGHvrud1cMFUrDbNg9QZVsaO7vG8gxLZqnQZX7ieMvUIrjibkVRlb7kLZdBjtXcEdVLWrORPg7vsKQemHVWAJ7aJE2lP1pyZ6B83Do722I_mYq8BG8SZyAUqaXceYKEV9GaN5iZGAb4oO6vAV07FXT4tM24LUh6It97qEakVDDCYGsQLKbjs1OoYNRTTq0ejLAiezCylITY3bpje-0QIthXq0Fb61Sro80IrRBCPKffmrrPICzrb1yrCjfPdkuUwCw1-2VFl_4kXQbMxqg_u0)

### 2. Діаграма UserLogin
[![Діаграма UserLogin](https://img.plantuml.biz/plantuml/svg/XPFFIiD04CRlWRp3qejwg0UFKef550HFIZqL92Ih1EgcPZTIRzLIUnFrK44GNo6M5ekrzHLcNy4dSNRpnwnQxMdPVlFxljcPR73XX28wQP8wf-5kSEmpsx8jnnL1IE01vh834taXBsKNXX3BFd6ubYfLnAdhS4hgcuUwacG_r9HoNeF1dUp90Oo8x19vaV1W36-oMp8W1qxJznn1DqFgSGs19nXZWZ4CvK0dkOG9WJaymnI1htZ2FmYC88QP79YqFNeQKIxMjcjP9BX7tRkY4BpzwDngmkX731hwH-TfNHf3nKVpeOupIeCK8IPYXvsfNf964iHZtiLCHLxKGuCj5uef4xxJv5jjbxQ47x0LqwRcka74n7x4MrdI6oJ6EAmPDWalo4GRjD0soW7cw52eeyoZtYA-4lYk7qJSV0c4lSWEdgOGguc-OrUgePXWBxtaJT7cgrmlGaq8Uj8IXfbjgJqXvR1SpTS8xxA5AaV9lRaPP9rKAZvpcv57gzMYFCMOe_z5NX3a5ldKlybjQud07Kpm3QVoMlRr_FGQguyYbbSur7jDDQQ-ce6JQ0fAsmAVEurWpEu_iJ68FyMsjO4d_A1jwnC0)](https://editor.plantuml.com/uml/XPFFIiD04CRlWRp3qejwg0UFKef550HFIZqL92Ih1EgcPZTIRzLIUnFrK44GNo6M5ekrzHLcNy4dSNRpnwnQxMdPVlFxljcPR73XX28wQP8wf-5kSEmpsx8jnnL1IE01vh834taXBsKNXX3BFd6ubYfLnAdhS4hgcuUwacG_r9HoNeF1dUp90Oo8x19vaV1W36-oMp8W1qxJznn1DqFgSGs19nXZWZ4CvK0dkOG9WJaymnI1htZ2FmYC88QP79YqFNeQKIxMjcjP9BX7tRkY4BpzwDngmkX731hwH-TfNHf3nKVpeOupIeCK8IPYXvsfNf964iHZtiLCHLxKGuCj5uef4xxJv5jjbxQ47x0LqwRcka74n7x4MrdI6oJ6EAmPDWalo4GRjD0soW7cw52eeyoZtYA-4lYk7qJSV0c4lSWEdgOGguc-OrUgePXWBxtaJT7cgrmlGaq8Uj8IXfbjgJqXvR1SpTS8xxA5AaV9lRaPP9rKAZvpcv57gzMYFCMOe_z5NX3a5ldKlybjQud07Kpm3QVoMlRr_FGQguyYbbSur7jDDQQ-ce6JQ0fAsmAVEurWpEu_iJ68FyMsjO4d_A1jwnC0)

### 3. Діаграма PasswordReset
[![Діаграма PasswordReset](https://img.plantuml.biz/plantuml/svg/dPFFIiD04CRlWRp3qejwg0yWfHIA1mzAQTLJGPPaXK1CD9lqpwsjO174GWyf2E8hrDfgRMtx2hDlv6msQHiH3-QKpCxyPhvl9mNkKyyFhcnIefpNNSyiCyvyNTCrQlYkH-09bg85Kz4M7N4B8nYABg6Sd77coQo0CuDoHiwA5r4bKGzcP5B4gWDz4S8O5h14oXmc-BOGFG8hHBOmE1UzJ8fNOOvPT4sMyE0PXZ0MeMXZ-L1qO4fWXeLZP4WqHaOmGTOOtXDycdZEFEkogPWHyINAdy08gLBaFvWLMcCdh5wgcp5p0AynzKtnbE8fV6vhVKXJZfmQjIqbDzQQJBLGfT5KLMStpeoaM0RrBTUHLOSDWrtBZxqq-DHrZwdJN5_AHZBAlOyaBGdE4y8NTkiG-42JLz8A38smNmmeivk0SP-d-kYQN0EIzRBvzG8aCLl5DfRZGR8ZsK0TRjtm0SdbBCUm0vFbyx-bRcp-aQfhEmJwQD8CPJoABbvHI717fj723iKTwXf4n6sJznEmQYEPhE7ZF77tRT_-pDMr0hxX7_GD)](https://editor.plantuml.com/uml/dPFFIiD04CRlWRp3qejwg0yWfHIA1mzAQTLJGPPaXK1CD9lqpwsjO174GWyf2E8hrDfgRMtx2hDlv6msQHiH3-QKpCxyPhvl9mNkKyyFhcnIefpNNSyiCyvyNTCrQlYkH-09bg85Kz4M7N4B8nYABg6Sd77coQo0CuDoHiwA5r4bKGzcP5B4gWDz4S8O5h14oXmc-BOGFG8hHBOmE1UzJ8fNOOvPT4sMyE0PXZ0MeMXZ-L1qO4fWXeLZP4WqHaOmGTOOtXDycdZEFEkogPWHyINAdy08gLBaFvWLMcCdh5wgcp5p0AynzKtnbE8fV6vhVKXJZfmQjIqbDzQQJBLGfT5KLMStpeoaM0RrBTUHLOSDWrtBZxqq-DHrZwdJN5_AHZBAlOyaBGdE4y8NTkiG-42JLz8A38smNmmeivk0SP-d-kYQN0EIzRBvzG8aCLl5DfRZGR8ZsK0TRjtm0SdbBCUm0vFbyx-bRcp-aQfhEmJwQD8CPJoABbvHI717fj723iKTwXf4n6sJznEmQYEPhE7ZF77tRT_-pDMr0hxX7_GD)

### 4. Діаграма ContentUpload
[![Діаграма ContentUpload](https://img.plantuml.biz/plantuml/svg/VPBDIiD0483lWRp3qejwgDwbb8Aq8EZDUYh8aYmII9EIRAH7cugzANXeGH1V8HIZ_OslCFj6pcoQsXGnXsN9pdppxSmsGia36NLTTkPxKdYotNDzRfk6QN1B-W63LyZKFSpKGCLg25D8r8ZnaBL34L1K50gBXuArpsxoL9P_658f8JiUJ20X0AnLZEidfB36_JE31MJwPqgh6bPAs6lkEZQNekMuGcFX7L9KIc6gnbejXXbJ3zfpXNxn2Muo-88LdTD90dDOxdERA1TS2iaBNNX1kvGkYZmafLhpGmkFoxddtXrPjRgoo7r3ds-omNMOCn0nWtd9hECT5gbucvOVTBbizYtHauxl7PLhNFd-1GzknRQTkdzhKa9wnaWMbbXYKPJHryGIn2woItJJeB6nQb2j_muCVsvdLutoarBFJrcjvdYM6zcYNlyhkjJ9lMZJE63OMB9SgYSrebuoDQ2fuNDAr2FEQAAXEpqzBiYRGiGKVNnBzaPWfpV_nvf60tVulatZ1m00)](https://editor.plantuml.com/uml/VPBDIiD0483lWRp3qejwgDwbb8Aq8EZDUYh8aYmII9EIRAH7cugzANXeGH1V8HIZ_OslCFj6pcoQsXGnXsN9pdppxSmsGia36NLTTkPxKdYotNDzRfk6QN1B-W63LyZKFSpKGCLg25D8r8ZnaBL34L1K50gBXuArpsxoL9P_658f8JiUJ20X0AnLZEidfB36_JE31MJwPqgh6bPAs6lkEZQNekMuGcFX7L9KIc6gnbejXXbJ3zfpXNxn2Muo-88LdTD90dDOxdERA1TS2iaBNNX1kvGkYZmafLhpGmkFoxddtXrPjRgoo7r3ds-omNMOCn0nWtd9hECT5gbucvOVTBbizYtHauxl7PLhNFd-1GzknRQTkdzhKa9wnaWMbbXYKPJHryGIn2woItJJeB6nQb2j_muCVsvdLutoarBFJrcjvdYM6zcYNlyhkjJ9lMZJE63OMB9SgYSrebuoDQ2fuNDAr2FEQAAXEpqzBiYRGiGKVNnBzaPWfpV_nvf60tVulatZ1m00)

### 5. Діаграма ContentModeration
[![Діаграма ContentModeration](https://img.plantuml.biz/plantuml/svg/XPFDIiD058NtWRp3q8swI1z0IcafBYjkT5MGa4OCn8pa1zfTjQ2kL4JgHd3hCfOMQslhAznv8yzC4kr4qK2IIRZvxZtdJ1fHR8TnSkAp5WzYDuZRlEk6Tkpnm3HCmtPY7Z9wf1LDQ2e6b8fpMea1ioEML_9G5YQHwzYHo_PRXzy4fWwKLdx0Eu46lH0ZSSDeZbTBT9ZAgnXMD6upiFq-biKXkNHBIqff8KRqAeOqLlFDIY0TiyjZxwZVJE9ZA2imJwWV0pB1_Prc6IJ5AwMMKXsnnttFwHzutCza5WWn44Dn9PkYBUHyW8RH90qJpJh1PkdBdPxZdih5bjwWRQFCuqcqBlMPvch21MXZd6-Pp0cmN_MvpnhNDBwIKZ0hjEfwJgQXnrPKv8vlirhD2nm_wRhrkkHjCBfJaXRYMbn2wuY9C-aQ8iYoV538iazLAoctbcotXvcx4lsBz7-_KUFSgxqamvUM5EuWkHNDaGCMoFC5rk4vsoSgev5ggUs8gkN_tKyt4tRcywrJv5GDrEE_CerF)](https://editor.plantuml.com/uml/XPFDIiD058NtWRp3q8swI1z0IcafBYjkT5MGa4OCn8pa1zfTjQ2kL4JgHd3hCfOMQslhAznv8yzC4kr4qK2IIRZvxZtdJ1fHR8TnSkAp5WzYDuZRlEk6Tkpnm3HCmtPY7Z9wf1LDQ2e6b8fpMea1ioEML_9G5YQHwzYHo_PRXzy4fWwKLdx0Eu46lH0ZSSDeZbTBT9ZAgnXMD6upiFq-biKXkNHBIqff8KRqAeOqLlFDIY0TiyjZxwZVJE9ZA2imJwWV0pB1_Prc6IJ5AwMMKXsnnttFwHzutCza5WWn44Dn9PkYBUHyW8RH90qJpJh1PkdBdPxZdih5bjwWRQFCuqcqBlMPvch21MXZd6-Pp0cmN_MvpnhNDBwIKZ0hjEfwJgQXnrPKv8vlirhD2nm_wRhrkkHjCBfJaXRYMbn2wuY9C-aQ8iYoV538iazLAoctbcotXvcx4lsBz7-_KUFSgxqamvUM5EuWkHNDaGCMoFC5rk4vsoSgev5ggUs8gkN_tKyt4tRcywrJv5GDrEE_CerF)

### 6. Діаграма ContentSearch
[![Діаграма ContentSearch](https://img.plantuml.biz/plantuml/svg/XPFVIW915CRl5_OT1c-g2tk0497Ie9kWnAw4cDQ119kDsTcmkrJ8BY8emY28w0t4MloN-WfdtgWpiwisKUd5ghFd--rtpdSs5qWgP7XM8pi-bupB8gF2EtKTrw6Uz0M1PvYgAnYeXcgg5lIWgzg41gGKCA6hme1vD62aj7CSIqdomPgKnInpU4NM3L9614OmXObgGgIlgfMoI4UqLgrGoGv29YuD2QKHseYWfph6JXC61FhGXPd-OyiBTUQ5aYL-ZFm11l4ZqR-HpkPMR6dH5_AG1M5D1aaFyAO7i6XUYusHFXwCrIqUc4CRiySlT0kn_nZpWfgHcIL-esA2ZeRVMYZpzKGL-pRQGjrZvxBgymsRl-ylJSxvE9WsTlWEKuBmIAEnMnZ2XnuoJF412zck7_BAN_3yTa48Z7wPemuEFj7m65le4hY7HwJbgQGdgC6KEVCqo2AwZjuHaXRfx78xy72nAEamlcEdlKKocIhtQc65PRE_bTlfhYot4_rHxZfh9DcDiRh3-KrKXwY6pWFZxQfh7EgJeLg9RYxWInEiZgjUIJnO-QoijWR-VxNhvF0Nlg-kymK0)](https://editor.plantuml.com/uml/XPFVIW915CRl5_OT1c-g2tk0497Ie9kWnAw4cDQ119kDsTcmkrJ8BY8emY28w0t4MloN-WfdtgWpiwisKUd5ghFd--rtpdSs5qWgP7XM8pi-bupB8gF2EtKTrw6Uz0M1PvYgAnYeXcgg5lIWgzg41gGKCA6hme1vD62aj7CSIqdomPgKnInpU4NM3L9614OmXObgGgIlgfMoI4UqLgrGoGv29YuD2QKHseYWfph6JXC61FhGXPd-OyiBTUQ5aYL-ZFm11l4ZqR-HpkPMR6dH5_AG1M5D1aaFyAO7i6XUYusHFXwCrIqUc4CRiySlT0kn_nZpWfgHcIL-esA2ZeRVMYZpzKGL-pRQGjrZvxBgymsRl-ylJSxvE9WsTlWEKuBmIAEnMnZ2XnuoJF412zck7_BAN_3yTa48Z7wPemuEFj7m65le4hY7HwJbgQGdgC6KEVCqo2AwZjuHaXRfx78xy72nAEamlcEdlKKocIhtQc65PRE_bTlfhYot4_rHxZfh9DcDiRh3-KrKXwY6pWFZxQfh7EgJeLg9RYxWInEiZgjUIJnO-QoijWR-VxNhvF0Nlg-kymK0)

### 7. Діаграма ContentSubscription
[![Діаграма ContentSubscription](https://img.plantuml.biz/plantuml/svg/ZPH1Qi9068NtWTnXSDDsOGzGH1JRheNYJYXZCj3G64ic4Rkp2dLJIYd5Gg7r2YeLWjPuXNzkr7zYZ9bWhLc4aCpxykQzFobnZxgUtxH9fULupF6k_0OtNElEirgEhkaQDRoMI-03Gj65G3o8dkZ35CPYG2WdDSvSkShdpA2SaLhbEWOq68aEN9JRWQuxC193-8QLXC8SnWIMyZI749QY1pDvpYdaoWqpRijjQja96KOmGrypc8fXvAy70K5g61jT8MKONJ_jOA4XGlvXhT8kHL-bLDsMmJYlqlicxczD-O89gaEOR0WXgXSOM2-hBXkUrQOUYsr4wXTy2QhGmphb0pmmjsbnZfcU9vHFtCKFgj-ajWjZcDQTuzH2vbZClEWOBEhYH0NM72epfWsRAK0bLGYH6FUQ4lp5Z1Ewn6NCJE8EqMI0sKJj9p518Csc1GfLr-JGaRoRBohZXlVJmvVtryypGtD62WNBCMpVPCNYFibsDlPAOXUPGJZaBPdsCn9TEoBmYkdCOI6UnK3ECS7wWwY0iNZ46NsFo6h_fnjyvZEKUDR1jipOaDhomJAro4IsO_zRcQwLy0h_CRhs2m00)](https://editor.plantuml.com/uml/ZPH1Qi9068NtWTnXSDDsOGzGH1JRheNYJYXZCj3G64ic4Rkp2dLJIYd5Gg7r2YeLWjPuXNzkr7zYZ9bWhLc4aCpxykQzFobnZxgUtxH9fULupF6k_0OtNElEirgEhkaQDRoMI-03Gj65G3o8dkZ35CPYG2WdDSvSkShdpA2SaLhbEWOq68aEN9JRWQuxC193-8QLXC8SnWIMyZI749QY1pDvpYdaoWqpRijjQja96KOmGrypc8fXvAy70K5g61jT8MKONJ_jOA4XGlvXhT8kHL-bLDsMmJYlqlicxczD-O89gaEOR0WXgXSOM2-hBXkUrQOUYsr4wXTy2QhGmphb0pmmjsbnZfcU9vHFtCKFgj-ajWjZcDQTuzH2vbZClEWOBEhYH0NM72epfWsRAK0bLGYH6FUQ4lp5Z1Ewn6NCJE8EqMI0sKJj9p518Csc1GfLr-JGaRoRBohZXlVJmvVtryypGtD62WNBCMpVPCNYFibsDlPAOXUPGJZaBPdsCn9TEoBmYkdCOI6UnK3ECS7wWwY0iNZ46NsFo6h_fnjyvZEKUDR1jipOaDhomJAro4IsO_zRcQwLy0h_CRhs2m00)

### 8. Діаграма ContentDelete
[![Діаграма ContentDelete](https://img.plantuml.biz/plantuml/svg/ZPB1Ji9048RlJVeE6oxg0H_044A2UlH0met4DEsOD85TizqQZeA9t3JnW0a7VGKae0XINs7sZPnj2tIh1tkQtSx_pR__RYDIdbHnhykQWYlWwXIweC1rNCVpbP0C9vZeMrpgWHxgEvpXL8-O5x5s1D9qnH7uNWIitRpCf3d7z5GiPeVZ4ovnZbDSum8tkD6F35UOK34q6sP0nIAI_YgKlKoV4l5LZt5E_JDSaAqv6HlYaj6oHBP1BUY96sY1BsJ0Cj3UIuxueCMtEQWjlH3gNCISPEPBfPEYPqRp5aQz8Vqd8Os1fCCFyyDlzMTz7wvLAFXHsLgaPEWh27Ry5tp3B-AyxrZxffngqLp7t0QhochzrptGl_BDLEEipqxtXDLg8VUxSG3r-b-gd6v7MLOLVLXyu_A0fQclSAqVz8Z26pCzCF7JmvhgUptMp-dWGkJ7MxEs6JCM-bG6kTT2Yl-Ik4w3AdhthlC3)](https://editor.plantuml.com/uml/ZPB1Ji9048RlJVeE6oxg0H_044A2UlH0met4DEsOD85TizqQZeA9t3JnW0a7VGKae0XINs7sZPnj2tIh1tkQtSx_pR__RYDIdbHnhykQWYlWwXIweC1rNCVpbP0C9vZeMrpgWHxgEvpXL8-O5x5s1D9qnH7uNWIitRpCf3d7z5GiPeVZ4ovnZbDSum8tkD6F35UOK34q6sP0nIAI_YgKlKoV4l5LZt5E_JDSaAqv6HlYaj6oHBP1BUY96sY1BsJ0Cj3UIuxueCMtEQWjlH3gNCISPEPBfPEYPqRp5aQz8Vqd8Os1fCCFyyDlzMTz7wvLAFXHsLgaPEWh27Ry5tp3B-AyxrZxffngqLp7t0QhochzrptGl_BDLEEipqxtXDLg8VUxSG3r-b-gd6v7MLOLVLXyu_A0fQclSAqVz8Z26pCzCF7JmvhgUptMp-dWGkJ7MxEs6JCM-bG6kTT2Yl-Ik4w3AdhthlC3)

### 9. Діаграма UserDelete
[![Діаграма UserDelete](https://img.plantuml.biz/plantuml/svg/ZLFDIiD06Bm7yWvBB-gXFe2KKcpgiKYXjuB4zCC6sqGs6-dHLj2RefGAWlWAeHXCMrjVuTityjlqBsiLFUqkEpFVCBDR2eJDHTXfite0t88s230Dqx0TuNE6ppYNLvZ8dkpBQnnX96-P7QHOXGe3SEm0MBryig2g2yOK9BVHQtZuY0c-OOHJZ766CtdFSB8jZL5Eqootm3a_1jvXIqrynPX8COxaC2NtCM7uITj8AUZi6dJyIx1iOQ_O6nTBfZhCvF1VPgf-pJrhYO2jpRoGaG-23jOM6jwkiki6WUjx5dWkD2jT1ou47VTqEHLFrHT7VkWr5t8_PKrXnGpVQObmJ7PLUWcEQKwM_ziCwx32kSyPo-Gt9yi99J31YE433aXAHNHAb1IiQPb6McYUvujwntIXLRv2P1exO8M2wpdji0d5uXO-NE0p7Nt3cyOEImkRu5JUKHsg9zbJpL4waRoX5_2Koch5xA-KCyEKCdG5UCsb4ItxVp6q9Fzcc4Q9TlIhJECB)](https://editor.plantuml.com/uml/ZLFDIiD06Bm7yWvBB-gXFe2KKcpgiKYXjuB4zCC6sqGs6-dHLj2RefGAWlWAeHXCMrjVuTityjlqBsiLFUqkEpFVCBDR2eJDHTXfite0t88s230Dqx0TuNE6ppYNLvZ8dkpBQnnX96-P7QHOXGe3SEm0MBryig2g2yOK9BVHQtZuY0c-OOHJZ766CtdFSB8jZL5Eqootm3a_1jvXIqrynPX8COxaC2NtCM7uITj8AUZi6dJyIx1iOQ_O6nTBfZhCvF1VPgf-pJrhYO2jpRoGaG-23jOM6jwkiki6WUjx5dWkD2jT1ou47VTqEHLFrHT7VkWr5t8_PKrXnGpVQObmJ7PLUWcEQKwM_ziCwx32kSyPo-Gt9yi99J31YE433aXAHNHAb1IiQPb6McYUvujwntIXLRv2P1exO8M2wpdji0d5uXO-NE0p7Nt3cyOEImkRu5JUKHsg9zbJpL4waRoX5_2Koch5xA-KCyEKCdG5UCsb4ItxVp6q9Fzcc4Q9TlIhJECB)

В цьому файлі необхідно перелічити всі документи, розроблені в проекті та дати посилання на них.

*Модель прецедентів повинна містити загальні оглядові діаграми та специфікації прецедентів.*



Вбудовування зображень діаграм здійснюється з використанням сервісу [plantuml.com](https://plantuml.com/). 

В markdown-файлі використовується опис діаграми

```md

<center style="
    border-radius:4px;
    border: 1px solid #cfd7e6;
    box-shadow: 0 1px 3px 0 rgba(89,105,129,.05), 0 1px 1px 0 rgba(0,0,0,.025);
    padding: 1em;"
>

@startuml

    right header
        <font size=24 color=black>Package: <b>UCD_3.0
    end header

    title
        <font size=18 color=black>UC_8. Редагувати конфігурацію порталу
        <font size=16 color=black>Діаграма прецедентів
    end title


    actor "Користувач" as User #eeeeaa
    
    package UCD_1{
        usecase "<b>UC_1</b>\nПереглянути список \nзвітів" as UC_1 #aaeeaa
    }
    
    usecase "<b>UC_1.1</b>\nЗастосувати фільтр" as UC_1.1
    usecase "<b>UC_1.2</b>\nПереглянути метадані \nзвіту" as UC_1.2  
    usecase "<b>UC_1.2.1</b>\nДати оцінку звіту" as UC_1.2.1  
    usecase "<b>UC_1.2.2</b>\nПереглянути інформацію \nпро авторів звіту" as UC_1.2.2
    
    package UCD_1 {
        usecase "<b>UC_4</b>\nВикликати звіт" as UC_4 #aaeeaa
    }
    
    usecase "<b>UC_1.1.1</b>\n Використати \nпошукові теги" as UC_1.1.1  
    usecase "<b>UC_1.1.2</b>\n Використати \nрядок пошуку" as UC_1.1.2
    usecase "<b>UC_1.1.3</b>\n Використати \nавторів" as UC_1.1.3  
    
    
    
    User -> UC_1
    UC_1.1 .u.> UC_1 :extends
    UC_1.2 .u.> UC_1 :extends
    UC_4 .d.> UC_1.2 :extends
    UC_1.2 .> UC_1.2 :extends
    UC_1.2.1 .u.> UC_1.2 :extends
    UC_1.2.2 .u.> UC_1.2 :extends
    UC_1 ..> UC_1.2.2 :extends
    
    
    UC_1.1.1 -u-|> UC_1.1
    UC_1.1.2 -u-|> UC_1.1
    UC_1.1.3 -u-|> UC_1.1
    
    right footer
        Аналітичний портал. Модель прецедентів.
        НТУУ КПІ ім.І.Сікорського
        Киів-2020
    end footer

@enduml

**Діаграма прецедентів**

</center>
```

яка буде відображена наступним чином

<center style="
    border-radius:4px;
    border: 1px solid #cfd7e6;
    box-shadow: 0 1px 3px 0 rgba(89,105,129,.05), 0 1px 1px 0 rgba(0,0,0,.025);
    padding: 1em;"
    >

```plantuml
@startuml

    right header
        <font size=24 color=black>Package: <b>UCD_3.0
    end header

    title
        <font size=18 color=black>UC_8. Редагувати конфігурацію порталу
        <font size=16 color=black>Діаграма прецедентів
    end title


    actor "Користувач" as User #eeeeaa
    
    package UCD_1{
        usecase "<b>UC_1</b>\nПереглянути список \nзвітів" as UC_1 #aaeeaa
    }
    
    usecase "<b>UC_1.1</b>\nЗастосувати фільтр" as UC_1.1
    usecase "<b>UC_1.2</b>\nПереглянути метадані \nзвіту" as UC_1.2  
    usecase "<b>UC_1.2.1</b>\nДати оцінку звіту" as UC_1.2.1  
    usecase "<b>UC_1.2.2</b>\nПереглянути інформацію \nпро авторів звіту" as UC_1.2.2
    
    package UCD_1 {
        usecase "<b>UC_4</b>\nВикликати звіт" as UC_4 #aaeeaa
    }
    
    usecase "<b>UC_1.1.1</b>\n Використати \nпошукові теги" as UC_1.1.1  
    usecase "<b>UC_1.1.2</b>\n Використати \nрядок пошуку" as UC_1.1.2
    usecase "<b>UC_1.1.3</b>\n Використати \nавторів" as UC_1.1.3  
    
    
    
    User -> UC_1
    UC_1.1 .u.> UC_1 :extends
    UC_1.2 .u.> UC_1 :extends
    UC_4 .d.> UC_1.2 :extends
    UC_1.2 .> UC_1.2 :extends
    UC_1.2.1 .u.> UC_1.2 :extends
    UC_1.2.2 .u.> UC_1.2 :extends
    UC_1 ..> UC_1.2.2 :extends
    
    
    UC_1.1.1 -u-|> UC_1.1
    UC_1.1.2 -u-|> UC_1.1
    UC_1.1.3 -u-|> UC_1.1
    
    right footer
        Аналітичний портал. Модель прецедентів.
        НТУУ КПІ ім.І.Сікорського
        Киів-2020
    end footer

@enduml
```


**Діаграма прецедентів**

</center>

