# GBS prophage integrase typing


## The method 

This repository hosts a database of **sixteen GBS prophage integrase types** (GBS*Int*1 to GBS*Int*12 and their subtypes) identified among **twelwe insertion sites** (GBS1 to GBS12) (Crestani et al., 2020). BLAST can be used to search for prophage integrase translated amino acid sequences in a query nucleotide sequence or in multifasta files with the command *blastx*. This prophage typing method is quick, reproducible and easily applicable on large datasets of genomes even by people with little computational experience.
To be considered the same integrase type, the threshold **percertage of identitiy (% ID) at the amino acid level** has to be **>= 95%**, and query coverage (QC) also has to be >= 95%.


|INSERTION SITE | PHAGE INTEGRASE TYPE | GENE | PUTATIVE ATTACHMENT SITE|
| --- | --- | --- | --- |
| **GBS1** | GBS*Int*1 | *comX* - 3' end | *att*L TTTTTTGTTATAATATAA**GA** <br> *att*R TTTTTTGTTATAATATAA**TA**
| **GBS2** | GBS*Int*2.1 <br> GBS*Int*2.2 | tRNA methyltransferase - 3' end | ATCCCCTCCTCTCCTTTAAT|
| **GBS3** | GBS*Int*3 | *rplS* - 3' end | *att*L GATTCC**G**GCAGGGGACAT <br> *att*R GATTCC**A**GCAGGGGACAT|
| **GBS4** | GBS*Int*4 | HU, histone-like <br> DNA-binding protein | CTCTTAAAGACGCTGTTAAATA<br>ATTCGTCTAGAAAAACCTTGTC<br>ATATCAATGTTTATTGATAGCGAC |
| **GBS5** | GBS*Int*5 | *rpsI* - 3' end | - |
| **GBS6** | GBS*Int*6.1 <br> GBS*Int*6.2| CatB-related O-acetyltransferase - 5' end| TGGAGCCGGTGGGAGT |
| **GBS7** | GBS*Int*1 | *hylB* - 5' end | *att*L TTTTTTGTTATAATAT**AAGA** <br> *att*R TTTTTTGTTATAATAT**GAGA**|
| **GBS8** | GBS*Int*8 | YbaB/EbfC family nucleoid-associated protein | TTTTGCATATTCATCATA |
| **GBS9** | GBS*Int*9.1 <br> GBS*Int*9.2 | Sodium/proton antiporter - 3' end | AAGGCGGTAGACGGATTTGAA |
| **GBS10** | GBS*Int*10 | DNA-binding protein WhiA - 3' end | - |
| **GBS11** | GBS*Int*11.1 <br> GBS*Int*11.2 <br> GBS*Int*11.3 | *comGB* - 3' end |  CTTTTAGAATGTTTGGTA |
| **GBS12** | GBS*Int*12 | 5-formyltetrahydrofolate cyclo-ligase  - 5' end | - |

![alt text](https://github.com/chcrestani/GBS_prophage_integrase_typing/blob/master/Map-1.png)


## Integrase gene types

**GBS*Int*1**
MIEKYTKKDGTTAYRLRAYLGVDPMTGKQVRTTRQGFKTEREAKRAEVKLIDDFQRQGAWKSNDKTTFDDVAKLWFEQYRNTVKPSTFLVNQNYYKTILKPHLGQLQMTKITVMICQKFVNCLSRYSGYRLYLSLANRIFKFAVNLGIIDNNPMSKTLRSKCTYKNMDTLTKKYYTKEELNAFLRIVEAEETLEMRLIYRLLSYGGFRIGELIALKDTDFDFRNNTISITKTIAYTKEGWAVQSPKTKKSNRTISMDAETMTLAKLYIKQSIKPLHGSFKLFNFASDTVRKRLDRFILKHGLKRITPHGFRHTHASLLFEAGIPAKIAQERLGHAKIAITMDLYTHLSKKSKDNVADKLAELVAI

**GBS*Int*2.1**
MASYRKLDSGWEYRIIYKDINGIRREKSKRGFSTKTLAKAAAVKAEREINSTDTELLDTTFYDYSIQWAEVYKRPHVTAKTWQTYSKNFKHIKHYFGNMKVKDITHTFYQKVLNEFGEIVAQQTLDKFHYQVKGALKSAVRDGIIRYNVADGAIVKSQVAKKSKEEKFLEESDYLNLIEVSKDKIKYASYFTVYLIAVTGLRFAEVQGLTWNDVDFDNGFLDINKSFDYSISQRFAPTKNEQSIRKVPIDLNTIDILKEYKDNYYQPNKLGRICYGASNNATNKAIKLTTGKPYPTNHTLRHTYASYLIMQGVDLISISQLLGHENLNITLKVYAHQLDKLKEKNDKVIKDIFYNL

**GBS*Int*2.2**
MAFYRKLGSGWEYRITYRDSQGKKREKSKRGFKTKTLAKVAAQQAEIDLNTMTADLLDITVLDYNRRWADIYKKPHITAKTWQTYTKNFKHIEHYFGTRKLKSITHTFYQQVLNDFGEKVAQQTLDKFHYQIKGACKMAIRDGIIRDNFADGAIVRSQKPVKEESEKFMEESEYLTFIKVAKSKVKYPSYLTTYIIAVTGLRFAEVQGLTWKDIDFDNGYIDINKTFDYSISQNFGPTKNEQSIRKVPIDKNSLELLRNFKSNYYQDNKLDRICFGASNNATNKVIKRVTGRNLTNHSLRHTYASYLIAQGVDLISVSKLLGHENLNITLKVYAHQIESLKEKNDHQVKNIFQNLKFDG

**GBS*Int*3**
MRYKTMWIEELANGKFKYIERYTDPLTNKYKKVSVTLDKNSSQAQKKAGLILQEKIEDRLAIRNHSEMTYGELKKEYLKQWIPTVKDSTKRGYLVSDSHIATVLPDDTIINKLTKRDIRLIIDKLLKHNSYHVTHKCRKRLHAIFSYAIQMDYMTSNPTENVLVPKPKDDYKPEKVLYLTSNEVYDLCNRMIDNDEQTLADIVLFMFLTGVRYGELACLTYDKIDFENKEILINATYDFNTREITTTKTKKSTRKISVSDNILDIVNKQKKTSSFVFPNSNGVPILNAYINKRLKIYGDYHTHLFRHSHISFLAEKGIPLNAIMDRVGHSDPKTTLSIYSHTTVNMKEIINKQTAPFVPFLKPE

**GBS*Int*4**
MRQKSMWSEKHKSGKVNFVERYKDPYTNKWKRTSVLMEKDTPRIRKEAQRILEAKIADIVRKLQTSDMLFTNLIDEWWIFYQQEIKRSSIVTLKGNIREIRAEFGINIPVVNIDPRYVQNYLDNLDCSRNKKERNKSMLNLIFDYAVSLDIIKDNPARRAKLPKIKKTLNDWKKIEEKYLEEEEIKRLLKELFRRPSTRRLGLLSEFMSLNGCRIGEAISIEPDNIDFKNKTLQLHGTYDRTNGYINGEKTSPKTLASYRETIMTKREMEIIQELEFINELEKNTNPRYRDMGYIFTTRNGVPIQINSFNLALKKANERLEQPINKNITSHIFRHTLVSRLAENNVPLKAIMDRVGHADAKTTVQIYTHITKKMKSNIADIMENY

**GBS*Int*5**
MKDKIITQVVSIMAEQLTMEQLEQLERVLAANLANVVMTENVSKVDETSNPKLLHLFISAKRIEGCSEKSLKYYKMVIEKMVAELDKPIRQISTSDLRTYLANYQKERQSSKVTIDNMRRIFSSFFSWLEDEDYILKSPVRRIHKIKTDKVIKETLSDESLELLRDTCDNIRDLAMIDLLASTGMRVGELVRLNREDINFHERECLVFGKGNSERIVYFDARTKIHLINYLDSRKDDSSALFVSLAYPYDRLMIGGVETRLREIGKRANLQKVHPHKFRRTLATRAIDKGMPIEQVQHLLGHVKIDTTMHYAMVNQANVKNSHRKYIG

**GBS*Int*6.1**
MRIESYKKKNGTTAYKFLLYAGYVDGKRKYIRRSGFSTRQSARAALINLQAELEKPKSSMTFGMLTKQWLKEYEKTVQGSTYLKTERNINKHILPKLDKVTIGDINPLLVQNLTEEWCSQLKYGGKILGLVRNILNLAVRYGYISNNPALPITAPKIKRERKTGNNFYTLNQLKQFLELVEKTDNIEKIALFRLLAFTGIRKGELLALTWDDLNRNTLSINKAVTRTQTGLEIDVTKTKSSDRLISLDDETLEILQQLHETFPSSTFMFQSESGGIMTPSLPRKWLLQIIKGTDLPQITVHGFRHTHASLLFESGLSLKQVQHRLGHGDLQTTMNVYTHITQSAIDDIGTKFNQFVTNKQLN

**GBS*Int*6.2**
MQIESYQKKNGTTAYRFRIYIGVIDGKKKYIKRSGFTSKKIAKQALMNLQQEIENPESKSTMLFHELTNLWLNNYEKTVQSSTYLKTKRNIENHILPSLGNYPIKDLTPLIIQKYADEWAVKLKYSSKIVGTVRNILNYAVKFQYIPSNPSDPVTTPKIKRTINKKKDYYNKDELKEFMQLVYDTDNIDIIATFRLLAFTGLRKGEMLALTWKDYRNGTIDVNKAIARDITGEYVGPTKNKSSERLISLDPETINILDELHETYPKTKYILESTAGRWISPTQPRRWLLQILSNSKSRLEPIRIHGFRHTHASLLFESGLTLKQVQYRLGHEDLKTTMNTYVHITESAKDDIGTKFSQYIDF

**GBS*Int*7**
MIEKYTKKDGTTAYRLRAYLGVDPMTGKQVRTTRQGFKTEREAKRAEVKLIDDFQRQGAWKSNDKTTFDDVAKLWFEQYRNTVKPSTFLVNQNYYKTILKPHLGQLQMTKITVMICQKFVNCLSRYSGYRLYLSLANRIFKFAVNLGIIDNNPMSKTLRSKCTYKNMDTLTKKYYTKEELNAFLRIVEAEETLEMRLIYRLLSYGGFRIGELIALKDTDFDFRNNTISITKTIAYTKEGWAVQSPKTKKSNRTISMDAETMTLAKLYIKQSIKPLHGSFKLFNFASDTVRKRLDRFILKHGLKRITPHGFRHTHASLLFEAGIPAKIAQERLGHAKIAITMDLYTHLSKKSKDNVADKLAELVAI

**GBS*Int*8**
MWHEEQANGNIKFIEYYKDPYTGKRQRAYVTLDRYTKQSETKARRLLNEIIECRIKSSGDQFVRFGQLVEEWKTSHSKTVKARTMKVYRHPIEKIKDFIGDDVLVKNIDARLLQKFIDYLKDRYSDNTINLIKQPLNMMLNYAVRMEYIMSNPMKNVVTPKRKKMSKKQFEDKYLETEQNQKIIEQLRDPIYGNHIANFSEIIFLTGMRPGELLALRWDHIDFEKLKIKIEYTLDYTTNGHANAELGSVKNDGSYRTIDIPLRVKEMLVEELNYQNTNDLRSDFVFITNKGKHLSINTINRRIKKTSEKLYGIVITSHSFRHAHITLLAELGIPLKSIMDRVGHTDVNTTIKVYTHATDKIGKQMMDKINKFVPIQSL

**GBS*Int*9.1**
MASYRKRENGLWEYRISYKTIDGKYKRKEKGGFKTKKLAQAAAIEIEKKLTQNILTNDEVTLYDFVKTWSEVYKRPYVKDKTWETYSKNFKHIKNYFQELKVKDITPLYYQKKLNEFGEKYAQETLEKFHYQIKGAMKVAVREQVVTFNFAEGAKVKSQVEPKNEEEDFLEEREYKALLALTRENIQYVSYFTLYLLAVTGLRFSEAMGLTWSDIDFKNGILDINKSFDYSNTQDFADLKNESSKRKVPIDSNTIDILREYKKNHWQANIKNRVCFGVSNSACNKLIKKIVGRKVRNHSLRHTYASFLILNGVDIVTISKLLGHESPDITLKVYTHQMEALAERNFEKIKNIFLVA

**GBS*Int*9.2**
MAYYRKRDNGWEYRISYKDESGKFRQKSKSGFKTKKLAQAAARDIEKKLSQNILTDGEVTLYDFVKTWSEVYKRPYVKDKTWETYTKNFRHIKTYFKDIKVKDITPLYYQKRLNEFGEKYAQETLEKFHYQIKGAMKVAVREQVIHFNFADDAKVKSQIESRAEENDFLEESEYKALLSLTRENIQYVSYFTLYLLSVTGLRFSEVMGLTWNDVDFKNGILDINKAFDYSNTQDFCDLKNNPSERKVPIDRKTIEILYVYRQNYWQANIKNRICFGVSNSACNKLIKKIIGRPVRNHTLRHTYASFLILNGVDIVTISKLLGHESPDITLKVYSHQMEALAERNFEKIKNIFLAS

**GBS*Int*10**
MRKVAIYSRVSTINQAEEGYSITGQIDSLTKYCDAMGWVIYKNYSDAGYSGGKLERPAISELIEDGKNNKFDTVLVYKLDRLSRNVKDTLYLIKDIFTKNNIHFVSIKENIDTSSAMGNLFLTLLSAIAEFEREQIKERMQFGVMNRAKSGKTTAWKTPPYGYTYDKENKVLLLNEFEATNVKQIFNMIVAGHSIMSITNYAKEHFAGNTWTHVKIRRILENETYKGLVKYREQTFAGNHDAIIDEELFTKAQLALDKRTNSQNNTRPFQGKYMLSHIAKCGYCGAPLKVCTGRPRVDGTRRQTYVCVNKTESGAKRGVNNYNNNKVCNSGRYEKSCVEKYVINELSKIQHDKEYLEKMKNNSKKVDVSSLKKEIKSIDKKINRLNDLYVNDFISLSKLTEEIKKLNKLKEGYHKTIKLNYVENKNEDVISTLVNNIDISKSSYDVQSRIVKQLVDRVEVTTDNIDIIFNF

**GBS*Int*11.1**
MNKVAIYVRVSTTMQAEEGYSIDEQIDKLKSYCKIKDWTVYDIYKDGGFSGGNIERPAMERLISDAKRKKFDTVLVYKLDRLSRSQKDTLFLIEEVFDKNDISFLSLNESFDTSTAFGKAMIGILSVFAQLEREQIKERMLLGKIGRAKTGKSMMFSKVSFGYTYDKLKDELVVNQAESIIVRKIFDAYLGGLSLNKLRDYLNNNGIYRGDKPWNYQGLRRILSNPVYIGMIRYREEIYPGNHKAIIDIDDYNKTQEEIKKRQIKALEFSNNPRPFRSKYMLSGIAKCGYCGTPLQIILGSKRKDGTRNMRYQCINRFPRNTKGVTIYNDGKKCESGFYEKADIEEFVINEIRSLQINYNKLDAMFDRHPTVNSDDIKKQIITLDNKLKRLNDLYINNMIELDDLKKQTQSLRKQKTILEDELLNNPAITQEKNKKHFKEMLATKDITKLDYETQKNIVNNLINKVFVKSGYIKIEWKIPFKKA

**GBS*Int*11.2**
MITTNKVAIYVRVSTTNQAEEGYSIEEQKDKLKSYCNIKDWNVFNVYTDGGFSGSNTERPALEQLIKDAKKKKFDTVLVYKLDRLSRSQKDTLYLIEDIFLENNIDFVSLLENFDTSTPFGKAMVGILSVFAQLEREQIKERMQLGKLGRAKAGKSMMWAKVAYGYTYHKGSGEMTINELEAIVVREIFNSYLEGMSITKLRDKINDTYPKTPAWSYRIIRQILDNPVYCGYNQYKGEVYKGNHEPIISEEDFNKTQDELKIRQRTAAEKFNPRPFQAKYMLSGIAQCGYCKAPLKIIMGAVRKDGTRFIKYECYQRHPRTTRGVTTYNNNQKCHSSSYYKQDVEDYVLREISKLQNDKKAIDELFENTNMDTIDRESIKKQIEAISSKIKRLNDLYIDDRITIDELRKKSTEFTLSKTFLKEKLENDPILKQQESKDNIKKILSCDDILTMDYDQQKIIVKGLINKVQVTADKVIIKWKI

**GBS*Int*11.3**
MYIEELDDGKYKFIERYIDPLTGKKKRTSVTLDRKTKQAENKARSILQNRISKKINNVTKVELTYGELRQEYLKQWLPTVKNNTIKNNTRYDEYISYLLDDDVLISNITKATIRNIANELGDKKSYNVVSKCMKRLSAILNYAASLDYIQSNPAKSVKVIKPVENYDADEKIEFLTIDEMRELYVQMTSKSNKIRDLVVFMFLTGMRYGEVVALTTDKIDFENKTIKINATYDYDGKELTTPKTENSVRVISVSDSILSIVNDFIVHNRMNNLITDHIFVSRYGNPMSIRYVNKRLKDFMPEKQLKTHVFRHSHISYLAEKNVPLKAIMDRVGHKNAETTLKIYTHTTNNMKEYINGQTNINF

**GBS*Int*12**
MKYTKTKYPNIYFYETAKGKRYYVRRSFFFQGKKKEITKSGLSTIPQARAALTEIERQINEQELGINTQLTVDQYWEIFSAKRLSTGRWHESSYYLYDSMYRNHIKDEFGFVKLKNLDRNGYEVFIAEKLKKHTRHTVHTINSSFMAILNDAVKNGNLAGNRLKGVYIGESAIPANNKKITLEQFKEWMDKAKEIMPKKFYALTYMTIFGLRRGEVFGLRPMDVTKNEHGRAVLKLKDSRSNRTLNGKGSLKTKDSERYVCLDDVGTDYIDYLIDEADRIKRSLGIIKEQKKDYLSINEKGLLINPNQMNKHFGLVSEAIGIHVTPHMMRHFFTTQSIIAGVPMEQLSQALGHTKIYMTDRYNQVEDELAEATTDMFLTRIR

