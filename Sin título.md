{note}Inicio de operación﻿﻿{endnote}

{clipboard}{key: enter}{wait: delay=+1s}

{click: selector=.main-content .collapsed; maxdelay=+6s}{click: selector=#noanim-tab-customers-tab-campaign}{wait: delay=+1s}

{if: 0%FEE == #noanim-tab-customers-pane-campaign > div > table > tbody > tr:nth-child(1) > td:nth-child(3)}

  {click: selector=.special-button}  {note}Ejecutando alternativa{endnote}
{else}
  {click: selector=.btn-social}{click: selector=#accordion-custom .btn-info}{wait: delay=+0.5s}{click: selector=#accordion-custom .btn-info}

  {click: selector=.btn-social}{click: selector=#accordion-custom .btn-info}{wait: delay=+0.5s}{click: selector=#accordion-custom .btn-info}

  {click: selector=.btn-social}{click: selector=#accordion-custom .btn-info}{wait: delay=+0.5s}{click: selector=#accordion-custom .btn-info}
{endif}

﻿﻿{site: path; trim=yes; selector=#noanim-tab-customers-pane-campaign > div > table > tbody > tr:nth-child(1) > td:nth-child(3)}
﻿﻿
﻿﻿﻿{site: text; trim=yes; selector=.text-success:nth-child(1) > :nth-child(3); page=https://crm2-soporte.cuballama.com/*}﻿