# Spancress 1.0 TEST
Native Android anchored ruler distance-multiset reconstruction. Android8+ min26/target35. Package com.gg007.spancress.

## Rules
Known turnpike reconstruction adaptation. Place six distinct marks on the integer ruler 0-12. Gold marks at 0, 12 and one printed interior anchor stay fixed; add three teal marks with the numbered buttons. The table gives the required number of unordered mark pairs at EACH distance d=1-12. Count ALL fifteen pairs, not just neighboring gaps; keep repeated distances. Example: marks 0,2,5 give lengths 2,3,5. Tap a teal mark to remove it, then CHECK DISTANCES explicitly. Six-mark cap, undo/reset, twelve puzzles, saved palette and optional live counts. Gold is required, cyan current. The visual ruler is continuous; the two button rows are only coordinate selectors. Each anchored board has exactly one solution.

## Download and status
https://mega.co.nz/#!JFlm3Dia!2OIUSJgMWqJWDQs1jSKwlMz8iTXkwk3LpMynV85Icxw
APK 16878 bytes; SHA256 a2401f2da8f8356652ad6283a37b4f48a1874028befb4a1a0c7016f4dc34b668. Original certificate SHA2561651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions; original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed921110 generates twelve distinct anchored distance multisets. Independent sorted positive-difference lists compare with production bitmask histograms for all8192 position masks per level:98304 comparisons. All2592 malformed-count comparisons pass. Each puzzle has exactly one solution, verified without assuming general turnpike uniqueness. Bounds, immutable anchors/endpoints, six-mark cap, incomplete entries, explicit check, solved locks, undo/reset pass. All12 actual drawing-adapter coordinate-toggle/check tap-solves pass; removal, menus/privacy/next/levels/saved palette/live-count overlay/completion pass. Eight drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All223 prior studio and803 legacy descriptions reviewed. Rankcress reconstructs a permutation from per-position smaller-to-right counts; Distfern places equal labels with specified gaps; Islespan connects a bridge graph. Spancress instead reconstructs six coordinates from the multiset of ALL unordered pair distances. No matching factory mechanic found. Known turnpike problem, not globally new. Original seeded clue boards, code and ruler illustration. Six full educational/community pages support the definition, multiplicities and reflection/nonuniqueness caveat. General uniqueness is false: the fixed interior anchor plus exhaustive enumeration establishes it only for these twelve boards. Signed/doubled/self-distance conventions differ; this app uses only positive distances once per unordered distinct pair. No biological, historical, complexity or broad reconstructibility claims used. Research-paper and package results were triaged but not relied on.

## Build and tests
JDK17/AndroidSDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/span-test src/com/gg007/spancress/Board.java BoardTest.java then java -cp /tmp/span-test com.gg007.spancress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your private signing material. No signing secret included. adapter/android contains the Java2D drawing adapter used with SpanAdapterTest.java, not an Android runtime.

## Privacy and branding
Spancress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, live-count overlay and solved-puzzle marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon, studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative224-card studio and publishing fragments privately preserved:
https://files.instinct.com/eg0y2k70kymc-spancress-source-archive
https://github.com/iLanis-agent/spancress holds README only, full Git source pending. Existing three studio includes and Pages settings untouched. Both sites verified separately.

## Rule sources
https://rosalind.info/problems/pdpl/
https://rosalind.info/problems/ba4m/
https://users.cis.fiu.edu/~weiss/cop3337_f99/assignments/assign9.html
https://math.stackexchange.com/questions/319878/can-a-collection-of-points-be-recovered-from-its-multiset-of-distances
https://math.stackexchange.com/questions/1957528/does-the-set-of-distances-characterises-class-of-a-finite-set-of-points-in-the-p
https://math.stackexchange.com/questions/2314059/uniqueness-of-point-placement-with-the-knowledge-of-interdistances
