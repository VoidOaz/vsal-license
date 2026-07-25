===============================================================================
VETERAN SOURCE-AVAILABLE LICENSE (VSAL)
Version 1.2 - Generic Source-Available & Auditable Software License
===============================================================================

Copyright (c) 2026 Berkay Kesgin / VoidOaz. All Rights Reserved.

-------------------------------------------------------------------------------
PREAMBLE AND PURPOSE
-------------------------------------------------------------------------------
This License Agreement ("License") is a legal agreement between the Author
(Berkay Kesgin / VoidOaz) and any individual, entity, or organization
accessing, inspecting, compiling, or evaluating the Software ("Licensee" or "You").

The Author has created and developed the Software to provide full source-code
transparency, static security auditing, and operational verification for server
administrators, developers, and security researchers.

The Author retains all intellectual property rights, copyrights, and proprietary
rights over the Software. Access to the Source Code is provided solely under the
express terms, conditions, and limitations defined in this License.

THIS SOFTWARE IS PROVIDED UNDER A "SOURCE-AVAILABLE" MODEL. IT IS NOT OPEN-SOURCE
SOFTWARE (AS DEFINED BY THE OPEN SOURCE INITIATIVE) NOR FREE SOFTWARE NOR PUBLIC
DOMAIN. SOURCE CODE ACCESS IS GRANTED STRICTLY FOR AUDITING, INSPECTION, AND
NON-COMMERCIAL TESTING AS SPECIFIED HEREIN.


===============================================================================
SECTION 1 - DEFINITIONS
===============================================================================

1.1 "Author" means Berkay Kesgin / VoidOaz, the sole creator and copyright
owner of the Software.

1.2 "Software" means the entire suite of source code files, compiled bytecode
(.jar, .class), build configurations, asset files, documentation, and algorithms
provided under this package.

1.3 "Source Code" means the human-readable programming language files (including
Java, XML, and build scripts) comprising the Software.

1.4 "Binary" or "Compiled Executable" means computer-readable bytecode archives
(.jar) or executables generated from the Source Code.

1.5 "Audit" or "Inspection" means non-destructive, read-only review or static
analysis conducted to verify security, performance, and absence of malicious code.

1.6 "Production Environment" means any live, public, network-connected, or
commercial server instance (including Minecraft server networks, proxies, or
containers) accessible by end-users or players.

1.7 "Non-Commercial Local Testing" means running the Software exclusively on a
private, offline, non-public machine or local environment (localhost) without
accepting financial payments, donations, or commercial benefit.

1.8 "Authorized Distribution Channel" means platforms, websites, or repositories
officially maintained or explicitly authorized in writing by the Author.

1.9 "Derivative Work" means any software or module that directly incorporates,
copies, or reuses substantial portions of the actual Source Code of the Software.
Independent implementations of similar functionality that do not copy from the
Software's Source Code are not considered Derivative Works.

1.10 "License Key" or "Validation Protocol" means a token, key, or online
validation protocol provided by the Author to authorize production execution.


===============================================================================
SECTION 2 - PERMITTED USES (TRANSPARENCY & AUDITING)
===============================================================================

2.1 Source Code Inspection
Subject to compliance with this License, the Author grants You a non-exclusive,
non-transferable, limited right to view, read, and inspect the Source Code.
This right is perpetual with respect to the specific version of the Source Code
you accessed, even if the License is later terminated for other reasons, provided
you do not further distribute it contrary to Section 4.

2.2 Security Auditing & Static Analysis
You are fully permitted to run static code analysis tools, security scanners, and
local profiling software on the Source Code to verify performance and security
integrity.

2.3 Publishing Audit Reports
You may publish independent technical reviews or security audit reports, provided
that:
(a) The reports are technical and objective;
(b) Vulnerabilities are handled in accordance with Section 8 of this License;
(c) The report does not reproduce entire source files beyond fair use code
    snippets necessary to illustrate findings.

2.4 Feedback and Community Contributions
If You submit bug reports, security advisories, or code contributions to the
Author, You grant the Author a perpetual, worldwide, non-exclusive right to
incorporate and commercialize such feedback within the Software. In return, the
Author shall publicly acknowledge and credit the contributor in the project's
documentation, CREDITS file, or an equivalent public attribution mechanism
maintained with the Software's official repository. This acknowledgment shall
remain in place as long as the incorporated contribution remains part of the
Software.


===============================================================================
SECTION 3 - PRODUCTION EXECUTION AND COMMERCIAL USE
===============================================================================

3.1 Commercial License Requirement
Running, hosting, or executing the compiled Binary (.jar) in any Production
Environment requires a valid Commercial License or explicit authorization
obtained directly from the Author or an Authorized Distribution Channel.

3.2 Non-Commercial Local Evaluation
You are granted a limited privilege to run the Software strictly for
Non-Commercial Local Testing. This privilege immediately terminates if the
server becomes publicly accessible or generates commercial revenue/donations.


===============================================================================
SECTION 4 - RESTRICTION ON CODE REDISTRIBUTION & COMPILATION
===============================================================================

4.1 Verbatim Code Reuse & Extraction
You may not copy, extract, duplicate, or redistribute the actual Source Code or
class files of this Software into other public or commercial projects without
written consent from the Author.

4.2 Redistribution Restrictions
You may not host, re-sell, re-license, or redistribute the Source Code or
compiled Binaries on third-party file-sharing platforms or unauthorized public
repositories.

4.3 Self-Compilation
Self-compiling the Source Code into execution binaries (.jar) is permitted
strictly for local debugging, education, and verifying that the official Binary
matches the publicly available Source Code (e.g., via reproducible build
comparison). Deploying self-compiled binaries into any Production Environment
without a valid commercial agreement is prohibited.


===============================================================================
SECTION 5 - INTELLECTUAL PROPERTY RIGHTS
===============================================================================

5.1 Ownership
All rights, title, and interest in and to the Software, including source code,
branding, and original assets, remain exclusively with the Author.

5.2 Notice Preservation
You must not remove, obscure, or alter any copyright notices, author credits, or
attribution headers embedded within the Source Code files. This obligation does
not extend to ordinary server log filtering or console output suppression
performed by server management tools, provided the underlying source headers
remain intact.


===============================================================================
SECTION 6 - THIRD-PARTY LIBRARIES & DEPENDENCIES
===============================================================================

6.1 Scope
This License applies exclusively to original code written by the Author.
Third-party libraries or open-source APIs (such as Spigot, Paper, Velocity,
Jackson, Guava, etc.) referenced by the Software remain governed by their
respective open-source licenses.


===============================================================================
SECTION 7 - SOFTWARE INTEGRITY & LICENSE VERIFICATION
===============================================================================

7.1 Integrity Assurance
The Author assures that official releases from Authorized Channels are free from
hidden keyloggers, destructive ransomware, or malicious data-wiping code.

7.2 Asynchronous License Validation
The Software may include a lightweight, asynchronous network protocol to validate
active production license keys. This process communicates only basic operational
metadata: the license key, a salted cryptographic hash (SHA-256) of the server's
public IP address (which does not reveal the plain IP), the software version, and
the runtime Java version. No end-user personal data, chat logs, player data, or
database content is collected, stored, or transmitted.


===============================================================================
SECTION 8 - RESPONSIBLE VULNERABILITY DISCLOSURE
===============================================================================

8.1 Confidential Reporting
If You discover a security vulnerability during source inspection, You agree to
report it privately to the Author before making public disclosures.

8.2 Resolution Period & Responsible Disclosure
The Author shall be given a 30-day window to inspect and patch the reported
issue. If a vulnerability is actively being exploited in the wild ("zero-day"),
a shortened 7-day notice period applies before public technical advisories may be
released for public safety. In all cases, disclosure must be coordinated to
ensure that users have access to a patch before technical details are widely
published.


===============================================================================
SECTION 9 - TERMINATION AND REMEDIES
===============================================================================

9.1 Automatic Termination
Your rights to execute, compile for deployment, or otherwise use the Software
(except for the perpetual source inspection right granted in Section 2.1)
terminate automatically if You fail to comply with any material term of this
License.

9.2 Consequences of Termination
Upon termination, You must cease all production and local execution of the
Software, remove all compiled binaries used in violation, and destroy any
unauthorized copies of the Source Code that were obtained outside of the
permitted inspection channel. The perpetual right to retain and inspect the
publicly available Source Code for historical/audit purposes survives termination,
provided You do not further distribute it.

9.3 Legal Remedies
Unauthorized commercial execution, unauthorized re-licensing, or willful code
theft constitutes a breach of contract and copyright infringement. The Author
reserves all rights to pursue legal remedies, injunctions, and copyright takedown
notices under applicable laws.


===============================================================================
SECTION 10 - GOVERNING LAW AND JURISDICTION
===============================================================================

10.1 Governing Law
This License shall be governed by and construed in accordance with the laws of
the Republic of Turkey, without regard to its conflict of law provisions.


===============================================================================
SECTION 11 - DISCLAIMER OF WARRANTY & LIMITATION OF LIABILITY
===============================================================================

11.1 Disclaimer of Warranty
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY CLAIM, DAMAGES, LOSS OF
DATA, OR OTHER LIABILITY ARISING FROM THE USE OR HANDLING OF THE SOFTWARE.

11.2 Limitation of Liability
TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, IN NO EVENT SHALL THE AUTHOR
BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, OR CONSEQUENTIAL DAMAGES
(INCLUDING LOST PROFITS, BUSINESS INTERRUPTION, OR DATA LOSS) EVEN IF ADVISED
OF THE POSSIBILITY OF SUCH DAMAGE.


===============================================================================
SECTION 12 - SEVERABILITY
===============================================================================

12.1 If any provision of this License is found by a court of competent
jurisdiction to be invalid or unenforceable, that provision shall be enforced
to the maximum extent permissible so as to give effect to the intent of the
parties, and the remaining provisions of this License shall remain in full
force and effect.


===============================================================================
END OF LICENSE TERMS - VSAL v1.2
===============================================================================
