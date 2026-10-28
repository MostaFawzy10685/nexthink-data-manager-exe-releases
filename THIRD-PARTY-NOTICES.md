# Third-party notices - Nexthink Data Manager 3.7

Nexthink Data Manager is independent software by Mostafa Fawzy, not affiliated with or endorsed by Nexthink (see LICENSE). It includes
the third-party components below. Each stays under its own licence, and each package's licence text is in its own folder
(for a Python package: the `<name>-<version>.dist-info` folder next to it in `Lib\site-packages` on Windows, or in the
`site-packages` folder of the bundled Python on Linux).

## Libraries under the LGPL (replaceable)

ldap3, psycopg, psycopg-binary, pymssql are licensed under the GNU Lesser General Public License (versions as in
the table below). They are included unmodified, as separate packages in the `site-packages` folder, and are not linked
into any other file. You can replace one by installing another version of the same package into that folder. Their source
code is available from the project links in the table.

## Programs bundled with the setup

| Component | Licence | Where to find it |
|---|---|---|
| Python 3.12 (embeddable package) | PSF License | https://docs.python.org/3/license.html |
| PostgreSQL 16 (EnterpriseDB Windows binaries) | PostgreSQL License | https://www.postgresql.org/about/licence/ |
| WinSW 2.12 (runs the service) | MIT | https://github.com/winsw/winsw |
| Microsoft Visual C++ 2015-2022 Redistributable (x64) | Microsoft Software License Terms for the redistributable | https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist |

## Python packages

Generated from the packages' own metadata when this version was built (licence as the package declares it).

| Package | Version | Licence | Project |
|---|---|---|---|
| annotated-doc | 0.0.5 | MIT | https://github.com/fastapi/annotated-doc |
| annotated-types | 0.8.0 | MIT | https://github.com/annotated-types/annotated-types |
| anyio | 4.15.1 | MIT | https://anyio.readthedocs.io/en/latest/ |
| certifi | 2026.10.23 | MPL-2.0 | https://github.com/certifi/python-certifi |
| cffi | 2.1.1 | MIT-0 | https://cffi.readthedocs.io/ |
| charset-normalizer | 3.5.2 | MIT | https://github.com/jawah/charset_normalizer/blob/master/CHANGELOG.md |
| click | 8.5.0 | BSD-3-Clause | https://click.palletsprojects.com/page/changes/ |
| cryptography | 50.0.2 | Apache-2.0 OR BSD-3-Clause | https://cryptography.io/en/latest/changelog/ |
| et_xmlfile | 2.0.0 | MIT | https://foss.heptapod.net/openpyxl/et_xmlfile |
| fastapi | 0.162.0 | MIT | https://github.com/fastapi/fastapi |
| h11 | 0.16.0 | MIT | https://github.com/python-hyper/h11 |
| httpcore | 1.0.9 | BSD-3-Clause | https://www.encode.io/httpcore |
| httptools | 0.9.0 | MIT | https://github.com/MagicStack/httptools |
| httpx | 0.28.1 | BSD-3-Clause | https://github.com/encode/httpx/blob/master/CHANGELOG.md |
| idna | 3.20 | BSD-3-Clause | https://github.com/kjd/idna/blob/master/HISTORY.md |
| ldap3 | 2.9.1 | LGPL v3 | https://github.com/cannatag/ldap3 |
| openpyxl | 3.1.5 | MIT | https://openpyxl.readthedocs.io |
| opentelemetry-api | 1.45.1 | Apache-2.0 | https://github.com/open-telemetry/opentelemetry-python/tree/main/opentelemetry-api |
| pillow | 13.0.0 | MIT-CMU | https://pillow.readthedocs.io/en/stable/releasenotes/index.html |
| psycopg | 3.3.6 | LGPL-3.0-only | https://psycopg.org/ |
| psycopg-binary | 3.3.6 | LGPL-3.0-only | https://psycopg.org/ |
| pyasn1 | 0.6.5 | BSD-2-Clause | https://github.com/pyasn1/pyasn1 |
| pycparser | 3.12 | BSD-3-Clause | https://github.com/eliben/pycparser |
| pydantic | 2.14.1 | MIT | https://github.com/pydantic/pydantic |
| pydantic_core | 2.50.1 | MIT | https://github.com/pydantic/pydantic |
| pymssql | 2.4.6 | LGPL-2.1 | https://github.com/pymssql/pymssql |
| PyMySQL | 1.2.3 | MIT | https://github.com/PyMySQL/PyMySQL |
| pyspnego | 0.12.4 | MIT | https://github.com/jborean93/pyspnego |
| python-dotenv | 1.2.4 | BSD-3-Clause | https://github.com/theskumar/python-dotenv |
| python-multipart | 0.0.32 | Apache-2.0 | https://github.com/Kludex/python-multipart |
| PyYAML | 6.0.3 | MIT | https://pyyaml.org/ |
| reportlab | 5.1.0 | BSD License | https://www.reportlab.com/ |
| smbprotocol | 1.17.0 | MIT | https://github.com/jborean93/smbprotocol |
| starlette | 1.10.0 | BSD-3-Clause | https://github.com/Kludex/starlette |
| typing-inspection | 0.4.4 | MIT | https://github.com/pydantic/typing-inspection |
| typing_extensions | 4.16.0 | PSF-2.0 | https://github.com/python/typing_extensions/issues |
| tzdata | 2026.5 | Apache-2.0 | https://github.com/python/tzdata |
| uvicorn | 0.54.0 | BSD-3-Clause | https://uvicorn.dev/release-notes |
| uvloop | 0.23.0 | MIT License | https://github.com/MagicStack/uvloop |
| watchfiles | 1.3.0 | MIT | https://github.com/samuelcolvin/watchfiles |
| websockets | 17.3 | BSD-3-Clause | https://github.com/python-websockets/websockets |

ReportLab's package folder also holds font files with their own licences (Bitstream Vera and DarkGarden, licence texts
included in `reportlab/fonts`). They are unmodified, and the reports use the PDF standard font Helvetica.

## Fonts and images

The product's wordmark image was drawn with the Outfit font (SIL Open Font License 1.1). The font itself is not included.
The product's own marks are the author's.

## Trademarks

Nexthink is a trademark of its owner. Microsoft, Windows, Power BI and Active Directory are trademarks of Microsoft
Corporation. PostgreSQL is a trademark of the PostgreSQL Community Association of Canada. They are used only
to say which systems this software works with.
