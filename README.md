# MongoDB
![image](data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxEPEhESEhIQFhIVEBgVGBgQFxkWFhUYFRYaFxUYExgYHSggGRolHRYXIjItJSktLjAuGh8zOjMsOSgtLisBCgoKDg0OGhAQGi0lICUtKy0vLS0tMjAvLS0vLS0tLS0tLy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0rLS0tLS0tLf/AABEIAKQBNAMBEQACEQEDEQH/xAAcAAEAAQUBAQAAAAAAAAAAAAAAAwECBAUGBwj/xABIEAABAwICBggDBQUECQUAAAABAAIDBBESIQUGEzFBUQcUUmFxgZGhIjLRI2JyscEVM0KS8AhzgqIWFyRDU1RjstKDk9Ph8f/EABoBAQADAQEBAAAAAAAAAAAAAAABAgMEBQb/xAA2EQACAQIEAgcIAgEFAQAAAAAAAQIDEQQSITFBUQUTIjJhcYEUkaGxwdHh8CNCMwYVNFLxFv/aAAwDAQACEQMRAD8A8m2zu071K9SyOK7G2d2nepSyF2Ns7tO9SlkLsbZ3ad6lLIXY2zu071KWQuyJ877n4nepWbSuaJuxbt39p3qVFkTdjbv7TvUpZC7LmTO7TvUrtwaXa9PqVky7au7TvUrtsio2ru071KWQG1d2nepSyA2ru071KWQG1d2nepSyA2ru071KWQG1d2nepSyA2ru071KWQG1d2nepSyA2ru071KWQG1d2nepSyFyPbv7TvUrxbI0uxt39p3qUshdjbv7TvUpZC7G3f2nepSyF2Nu/tO9SlkLsbd/ad6lLIXZsKGV2H5nbzxKpJamM27mRtHc3epUFLsbR3N3qUF2No7m71KC7LXSOsfidu5lAmzU7d/ad6laWR03Y27+071KWQuxt39p3qUshdjbv7TvUpZC7G3f2nepSyF2Nu/tO9SlkLsbd/ad6lLIXZLFM63zO38yoaRKZRbmBPRUjpnYW+JJ3Ad62w+HnXnlj/wCGdatGlHNI237GgbZrpvj5XaP8pzXqf7dh4vLKp2vNL4HB7bWfajDT1+Zh1mjXQHOzmncf0I4FcWJwU8O9dU+J0UsTGqtNGY9lymtzHkGZVGtTWOxFIFSRpEjVSxUFaQqSh3RYriWntNTmRYYk9pqcxYYk9pqcxYYk9pqcxYYk9pqcxYYk9pqcxYYk9pqcxYYk9pqcxYYk9pqcxYYk9pqcxYYk9pqCxauckIAgCAIAgNjQfL5lUluYz3MhVKBAEBR+4+CEo061OgIAgCAIAgCAmh3eahlkXLYwNlo3SLYY3izto69iLWGXw3z4G69DC4yFClJWeZ7P0048zkxGGlVnF30X6zAkieBic11jxcDY3z3neuKUJpZpJ2fFrf14nTGUW7JrQ3tM4vpHYs7XsT3HL3yXs0254B5+F7em32PMqJRxSymoXjHeQSbyqvc1jsQy8FSReJGqFwgCAIAgCAIAgCAIAgCAIAgCAIAgCAIDfO0RPTRQvmiexszDJGXgjE3EW8eOV7cnNO4hZtpvQyqJpkSgzLhGSC62Qtc8r7vyUXV7EOSTSLVJJl6ZghjeWwTGaPZtOMsMfxFgLxhJO4kj/wDLkr8SzST0ObWpuEAQBAEAQBATQ7vNQyyLlsYGVRTtF432EbjdxAu4WFxh8wOC6cPViv45917vj4W9fAwrU2+3DvLbl6mdDVRy/Zyloij+Q5tLg34W4ufw8rLsp16Vb+Kq1kjtwbtor+nkc86U6fbprtPfw4v4la/SLXgRxC0Ytwte24AclGLxkJx6qkuyviRRw0ovPU3Zr15x1EEm8qjNY7EMvBVkXiRqhcIAgCAIAgCAIAgCAIAgCAIAgCAIAgKg2zG/uQHT1es1ZWwwx1E8j2wtwtDnE4syQ6TP4n2dhuc7Ad5OWRRehnVm3oY1JTmV7WN3k+g4kqs5qEczOerUVOLkzrTRsZHswPh4348ye9eZ1kpTzPc8RVpyqZ29TltI0mydb+E5tP6HvC9GlUzq57FCr1kb8TEfuPgtDdGnWp0BAEAQBAEAQE0O7zUMsi5bGAQBAAUBXEeZS4siF5NzvWbepokrFt1BJRAEAQBAZui6Nkz8LpAzu4u7mk5f1uXXg8PCtPLOVvm/Lh+7HPia0qUbxjf6efE2GmdERRNxNfhPZcScX4eN/bwXdj8BRpRzRlbwet/Lj9PI5MJi6tSWWUb+K4fT6+Zol4x6YQBAEAQBAEAQBAEAQBAEBsaD5fMqktzGe50+q0P7x/g0fmf0XBjJbR9TyekZ92Hr+/E3c+7zXJHc8+nuanTMOKIni34vr7fkumhK0/M7sLPLUtzOafuPgu89ZGnWp0BAEAQBAEAQE0O7zUMsiPEVa7KWQxFLsWQxFLsWQxFLsWQxFLsWRRQSUQBAEAQBAEBc5xJuSSeZNz7qXJyd27kJJaItUEhAEAQBAEAQBAEAQBAEAQGxoPl8yqS3MZ7nX6sH7J394f8AtavNxffXkeJ0h/kXl9WbOfd5rnjuclPcwa793J/du/Iran315nVR/wAkfNGr1T0TFW1UME0zYmPeAS6933PyRkAgPduBdYZ8TYH0ZOyue5CKlKzOZ0rSMhmkjjmjmYx5AliDg14HEYgPa45EjM6Rd1c6JKzMRWKhAEAQBAEBNDu81DLIhUlQgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIAgCAIASgOz1a1G0lVMBZSyNYT88/2TbcCMdi4fhBWM5xT3M5wdzsqbo/rKCGWWV8DgLEshLnEAb3XLRuvn4LixLUkmuB53SGHbhnXD5fg1s+7zXLHc8inuZOi9V59JMlbE5jA0C7pL4SSflyG+wPh5ropaSuz0sHSc55uCNVpXo00pACRC2UAHOmfiPk12F58gV2qpFnqZHc88qIHxOcyRjmPabOa8Frmnk5pzC3TT2N2miNSQVQCyAWQCyAogJod3moZZEKkqEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQBAEAQEtLTvleyONpdI97WNaN7nPIa0DxJAUN2VyUrn0p0fdGdNoxjJJWsmrLXMjhdsZ7MAO4Ddi+Y57gbDknUcmbRjY3Wt2s9Po5odKSXO+SNli99t5zyDRcXJ9zklOjKo7IwrzUXdnmGlek+tkuI2QwsIy+HaOtmPmf8JG/wDh5rtjg6a31OOVeT2RqtGVIlp6p77B8TGuyAAdd1tw3X3eYXJUwKVRZXo/gcUMIrTafL5l2g9e6yjbgj2JjxE4Xxjjv+JpDifEnguz2Olax0UpunHKtj0jVDpAgrnthkYYZz8oJxMf3MdlY9xHgSuSrhpQ1WqOunVUnY6HWnVSj0nHgqYg4gENkbYSx34xvtcc7Zg8QVlGTjsdzVz5k131Wl0TVOp5DibYPjeBYSRm4BtwIIII5jkQV1wnmVzGUbGiYFcqX2UAWQFrwpBYgJod3moZZEKkqEAQHQTak6SZAal1JKIBFtS+7CMFsWKwde1s9yp1kb2uXyM59XKHQaP1J0lUQtnipJXwuBc14LQCASCQC4G2R4KjqRTsXyM58FXKBAEAQBAEAQBAEBu9CapV9cx0lLTSSxteWFzS0AOADiPicODmnzVJTinZllFsyazULSsLS99DU4RvwNEhHeQwk2RVIviTkZzd1cqdX/q20x/yM380f/ms+tiWyM1emtWK6hAdU0s0TSbBzm3Zc7hjbdt+66spxexDi0ahWKhAEAQG+1DrW0+kaKV4uxk4Lu4WIJ77Xv5K0KLrPq47siVRU05PY+tY3hwDmkEEXBBuCDuIPELzmmnZnSnfVHlXTDq9O+WOsjYZImwiN7Wgkswuc7EQM8BxZ23W7124SpFLIzjxVJt50cVrDp4aQbTNZTQxmKBrCYWm5IJybnlHmCAcwS7PNbxiqV3KXv8A3c5K1ZSSurWMGGlqGskaG2bIGhwJbmGuDxxyzAWbxdC6d9vBnP7RBJq+5hzUz2fM0j8vUZLeFaFTuu5aM4y2Zv8AUPV+etqoXRtcIopmPfJua3A4OsDxebAADnfcq16kYRafE6aFOUpJ8D6HXknqngP9oTSEctVSxMIJiikDyODnlhw+IAv/AIl3U6EoU4zl/a9vS2pzyqRlJxXCx5ZCN6sQS4VAGFAWSjJAQqQTQ7vNQyyIVJUICjtx8EJW59daCMZoaKKXCRNSRxBrtz70+Jzf5WuPgCuB7m58z12qcrNJu0Y2+PrIia45/A6zmSOt/wBMhx811qfYzGWXtH1DDBFBTup4rBsFOIw3sgMs0HvsB/RXIbHzR0e6iVGmXuDHNihjAxyvBdYkZNY24xu4nMADecwD1zqKKMlG7O2l6HaWdsraHSccs8WT2OLHgOzAa/Zm8eYO8Hccln1z4otkRx+omo50hXT0VQ+SB8ML3usA5wdHIxhabm1vjJuOQWk6lo3RWMddTstHdC8JkkjqK/BIXv2UTMG1MbXENkeCc7gXsBlz5Zus+CLZEcFrhqXUaNrGUd9q6XDsXMGHa43YGixJwuxZWueGea0jUTVyjhZndu6GqeCFhrNJRwzyWa2+BsWMj5G43AyHwtfks+ub2RfIjV619FX7O0c+skqHGdmzDow0bO75GxnC7eW/FcZX3KY1rysQ4Kxj6k9Fzq2n67V1DaWlsXNLgMTmC4L3FxDY2cib3GdgLEzOrZ2REYczJ1m6JxHSurNHVbauFrS5wGEktbfG6N7CWvIsbiwOR3nJRGtraRLhyOv6BZC3RVY4bxWSkeIp4SFnV75aGxx+gumrSEcsZqtjLAXDGGswPDTvLC02uN9iDfdlvGkqKtoVU9bGw/tA6txROhromtbti6OXDkHPw4mPtzIDgedm96rSlo0TJcTvelnSukaWnp3aO220dPZ+xhExwYCcwWOsL2zWdPLftFpXtoY2jdKzzaDqZNNRiO8crPtG7N0jMNoyWZYZC8kAAA5NI3qWu12Rw1Pm4LsMGEICAIDN0N+/i/F+hXXgP+TDzOfF/wCGXkez6F1irtFMiEjC+mkYHsDzlZwv9k8Xwnm038Be69bE4LDY6UsrtNaO3hzXHz+JwUcTXwyWZXi9vwzuNF6/UM9sUhidymFh/MLt914dfofFU9lmXh9tz06XSFCfG3mZMmhNG1ZLxHTPLsy6BwBcebnRkF3mvOq0qi0qJq3O5pOjQr6tJ+X4Mc6hUPZlHhIf1WGRGP8AtmH5P3slZqjo6IXfCwjjt3FzT4tecPsrwg73itfAvDBYem7pe9/cvqta9HUrQ3bRWbkGQfHa3ABlw3zsu+l0biqr0g/XT5lp4yhT3kvTX5HFaw9JMkoLKVhiacsb7GS33QLhvjcnwXuYToKEHmrPM+S2/PwPMxHSjkrUlbx4nj+t7iXxEkkkPJJzJJLbkqOmVaVNLk/oT0Y21Nvw+ppqYb/JeIz02dfqVqJU6Wc4xujjhY6z5HkOLTa9mxg4nG3Ow71nOaiTGNzY689GdRoxrp2SMmpgRdxIZIy+4PaTZ3DNpJPIKIVVLQmUbanA1Ay81qiiMZSSTQ7vNQyyIVJUICjtx8EJW59Ca96UfRaH0TUx/PDNRvAvbFaB12k8iLg9xXJBZpNGz2OpZoaknq4NNBzbCgIBIywuAe2W/AhjpG+Du5Uu7WJNB0XaadpCDS1Ubja10haDvDBBG2MHvDA0eSmccrSCdzWdDd36Cq2U+VRiqALb9q6JuyPpg9O5Wqd/ULY47oCp5f2m4ta4NZSyNlyIw3c3C13I4m7vunkVpVay2RSCd2dxq29h1q0ngtbqIBtuxDqod75eN1m/8aLcTz/TUrv9Jg65xftaBt752xxtt4YcvBaJfxFX3j0XpAexundAl9rYpBn2nENZ/mLVlHusu9zlP7QtHO6spX4HugNMI2WBLdrtHl7cv4iDH427lpQa1KTudLrzBLHquxkwcJW09I1wd8wIkiyd3jcVnDvl3sWdJTXSau0ppr7ER0rnBv8AwQwWuOQdsyeVlMLKepEti3+z4x7KGrfJlA6pLml3ynDG0SOF94yAv908krNOWghsOgux0TXYQbdbmsONurw281FTvCOx49oLVKtrZY4Y6ecFxDS90bgyMHe57iLAAZ9+4ZkLolNJFFF3PVP7ROkI2U9HRg3fjMxHFrGMdG0u/EXm34HLGkt2Xkzqel7WSs0dT08lGQHvnwOuwSfDgJ3WyzAVacU3qS2YepEkmsNDM3StKw4ZC2OQx7NxBaLvjvm1wNxibYcOBunaMuywtVqfO8zA1zmhwcA4gOG51ja47jvXYjB7liEBAEBmaHNp4vx/mCAurAu2Ih5nPi1/DLyPZNA6QlZEGQPjmYW/aUtUAQT/ABGK/DjkeOd17OKowlPNUTi+E4/U8/D1JKFoNNcYv6FJ2aMkNpYquikzuG/aRX8HDF6ABTF42C7Eo1F7n9veJLCyfbi4P4EX+jFI/OPSdKf75piPniKt7fiI9+hL0d/kVWEpPu1V66GFpbRLqVgc2spZQX4cNNMXuGRNy22Qyt5hb4fEqvKzpSjxvKNjGrSdKN1UT8maUhdxy3ZfBGHOa0uDQXAYnbm3Nru7hvVZPLFu1yYrNJK9jZVdFTRCpaZy+Vj2iIxC8UjSfjJd3D3HHhzU6tabhLJaLTvfdcv35G86dKCks12trbM4XW0/FF+F35j6Lyemn24eT+h39Gd2Xp9TV0Ivfy/VeIz0ZOx1Or9FUwSNnZLJA8bjGbPI5EbsPc4Edy9HD9GSqa1dFy4/g4KvSEYaQ1fw/JLrTUVVdIZJpnykE4WusGsH/TaLNb6XPElUq4BRv1Xu/JenjHJds5WtYQLEEG/FcNmnZnXFp6owVJcmh3eahlkQqSoQAhAdprN0hS19DBQugjY2HZWe1xJdsmFguCLC97rKNPLK5o53Vi2n6RKpmjHaMDWYCxzNqScYje/E5lt1rFze4HuU9Us1xn0L9SOkSXRNPNTsgjkEsheXPcWkXY1lgAPu3UTp5ncRnZGr1K1xqtESF9OWlrwBJHICWPDdxyNw4XNiOfHcrTgpIhSsdvpHpxqXxubBSQQyO3yFxkse0G4Wi/jcdxWaoc2W6w43UvXKXRdVLV4BNJLE9jtq4gkySMkc8uAJJuz3Wk4ZlYrGVmYtZrG6XSH7QMbQ/rbKjZ3OG8bmuDb77HD7pk7OUZtbm11w1xl05UUhcyKncx2za/aOwtMj22e91rsDSAbjdvVYwyJkuV9j1atr9aKOKOMQUNW8tttYsV2kG32jXOYHEjO4AHPvwSgzTUh6UKiSDQDIqyQGrl2IdmCXSiRsstrZWGF27Ldbgppq89CJbHnGpHSfV6Lj2GCOenBJayQlrmXNyGPF7NJJNiDvystp0lLUpGdtzJ1v6WauvgdTRxR00L24XiNxe97TvZisA1p4gC53XtcGI0Undhz5GNqH0lS6HgkgZTxyh85lxPeWkFzGMtYA5fAD5qZ0szvcRnZG9rOnStc0iKmpmO7Ti+S3gPhz8VVUFzJ6w8z0vpKaslfNUSOklf8AM51vAAAZADgBYBaqKSsimbW56n/r4qP+Sg/9x3/iseo8S/WI1WsXTLX1cToY2Q07XtLXOjLnSWORDHGwblxAvyIVo0UtyHU5Hmy2MwgCAqiVwVFxmMiM/BaKEt0Q7M7/AFVp6uuifJHTzOEVsT2N+En7nEu3Eht7XC+hw/SdNpQrNKXwf29Tx6/R9SLzU9V8UbWHTdRHdhdiANi2YYvI3z912SwlGfaSt4rQ5liasdH8SQaYjPz0lOfwAs/K6r7LNd2pL11JWIjxgjGr6yKRoEcDYziuSHl1xY5WI/qy0pUqkHeU7+hSpUhJWjGxgrcwCAypNF1WwfUtpp3xMFyWNJuObRvc0cSL2GZXHiMfQoPLKXa5ffl6nXRwVWrqlZc2edVtU6Z5e61zuA3AcAF81iJ1K03OX/iPbo0o0oZIkmjdIPp342hp4EOHDuO8Hw91WjWlRnmS95FajGtHKzsdF6biqLAHC/su3n8J/i/PuXuUMbTq6bPl9uZ4lfCVKWu65r68jG0hXRw3xHO5s0ZuPl9VzVq0abdzejSnU7qOZ0lpJ053ANG4bz5leZWrOq9j1KNBU1uYKwNiaHd5qGWRCpKhAEAQBAEAQFUAQBALIDotF69aUpWCKGsmbGBYNdheGgbg3GDhHcMlR04sups1OltL1FY/aVE0sr7WBkcTYcmjc0dwsrKKWxVtswlJAQBAEAQBAEAQFbK8YNgvhic9zWta5znEBrWglzidwaBmStFCK1Y1YewtJaQQ4EggixBGRBB3FaK3Ahmy1W0T16spqa5aJZmtcRvDd7y3vwg277KlSWWLkTFXZ9b6PoYqaNkMLGsiY0Na1u4Af15ryG23dnSeX9MemWskZTMii2hiEjpXMaXhpcQ1sZIy+U38l6WAnVh2oyaXK+nu2POxqi3Zo80FY/uPiPovYj0jWW9n6fax5jw0GXdedyC0/wB0qckV9ljzZQ1rvuqj6TrPZL99SVhYeJvdSNOCCriEsUUrJJGsONjS5hc6wfGbZEE58wuHF4ivVg+215afI6sPCEJLQ+hV4J7Z859OOrcVFWRywgNZUsc8sbkGyMIDy0cA7E0+N+a9HCzco2fAxqLiecLqMxZUdNMXKhrnusMTnE8LucT+ZWU4tdpv1F1FckS1lDLCQJGObfdfcfAjK6xhUjPuu5SnWhUV4O5jq5oTQ7vNQyyLdk7l+SvlZnnQ2TuX5JlYzoo6MjeFDi0SpJligkIAgCAuAQFbIBZALIAQgLEAQBAEAQBAEAQF1lvGmluQFoD0foo13odGOLKmlaHOJ/2qMF8gB/he03Ib+DkLtJzXLiKMp6p+hpCSRB0p65UWlJB1akaHNOdS+7ZZAMrBrf4d1sdz3NV8Nh5x3YnNM5PVqpdBV08rDZ7JQ4crtzz5helRoRnNRls9DlrVHCm5Lh9z6l1Z1lgr4w5hAkA+OMn4mnjbtN5EexyXjY3A1cLO0tuD4P8APgb4bEwrxut+KNfrzqVFpRrXYtnUMFmvtcFt74JBxF725XPeDjRrun5Fq1BVPM8rq+jvSEJOKEvaP4qc7TF4DJ3q1dFTGpLsK7PNrUasNo38v25iHViUZGnqr98b7/8AauR46tyXuORuv/1fuZLFqPWy/uqef/1W7MfzPsFvSxzbtNeqNqUa03Zwfy+Z3WpPRn1aRlRVvY6RhDmRx5sa4Ztc9x+YjeABYEbyprYrMssT0qOGyvNI9B0hXRU7DJK9rGDeXfkOJPcM1z0qM6slCCuzpnOMI5pOyPnHpd1gOkKmJ4BETWObGDvtcEud3k/oOC+heAWHpxi+87t/D5HBRxPXyk1srW+JwhCwlBo3KstcXva+dt9uNr8Vm720DvbQ7zV1tLh/2exdb4sX7z/FyHhkvBxbr5v5fTl6ftz5/GOvm/l24cvT9ubKrEZY7a4MFs8dsPndc0M2ZZd/A5abmpLJe/gedaWEAkPV8eD726/3L528V7NPrLfybn0uH63J/La/h9eHuIId3mrs6UZC6TkCAjn3Ks9i8NzFWJsEAQBASMCgF1kAsgFkBRwQESkBAEAQBAEAQFwW9ONlchhaAICoC0hC+rILluQZeiP38X4v0K3w/wDlj5mGK/wy8jqxXSU78RxtsbtkjuC2+69sxlxC9KdW11UjePPdeTR49OF7Om7S5fY7LQ3SVVsABfFO374+K34m29wVwVOiMHX1pu3k/o/wdcekMRS0mr+Z0tN0pxn95TSN/u3h35hq4Z/6en/Safmrfc6Y9LQ/tFmWOlCj/wCFV/yx/wDyLL/5/Ef9o+9/Y0/3Wjyf76kM3SjTj5IJyfvljfyJVo/6fq/2mvS7+xV9LUuEWaXSHSdUvyiiii7zeRw8CbD1BXdS6Aox1nJy+H3fxOap0tUfcSXxOQ0lpOapdjmkfI7hiOQ54RuaPAL2KNCnRjlpxSX77zzqtadV3m7nJa1fNF+F35tXD0h3o+p6PRvdl6fU0a849IoQsZw4okrFI5pDmkhw3FpsR4FYuKkrNESSkrPY3UlDV1QxSv3D4Wvy/wAoFmnvtddeG6JkotxSj57v9/UeesRhqDywXm19+PyNNU074zhe0g9/HwPELlr0ZQdpKzO+nUjNXi7iHd5riZsjIXUcgQEc+5VnsXhuYqxNggCAICeEZeagF+FCDPptB1UsL6iOnmdAz5pGsJYN98+NrZ2vbjZQ5JaFsrtcwAFJUo8ZHwQGMpJCAIAgCAIAgLl1kBAEBcF1Q7qKlVIJqKYRyMedwcCfDcfZaUp5JqTM60HOnKK4o9KptJxvY1k7MbA0Bj47CRreFjucPFdlTBVIzdbCzs5auL1i/HmvNHzTi0yGXV2mmN4por33SXif67nFc068of8AIw8l4w1XnpZr1NY4ipHT8kbtUKpvymUj7sjXDyuVVdI4PbrpRfJp/Yt7VF7xXuIn6HqKf4pceE/CMQG/fwPIFd2DxVKrNqFXNpsVnUhJWjFIsXomZfA5oc0ubiaHAube2IA5i43XGV1Ek3FpOzLRaTTaujY1WlGWqI4YImRSva5uO75Iww3AY8nK+d9+8hc0MPK8J1JtyintonfmjedeNpRhFJP3r1OE1lqA6RrRngBB8TbLysPVcWOqKU1FcD0Oj6bjTcnxNQuI7wgLFyFjPptLzRtLQ64tliFy38P/AN3C66eNrU45U/fwOWphKU5ZmvdxMOWRzyXOJJPE5rmlKUneTuzojFRVoqyKw7vNcMtzVGWvpDjCAjm3FUnsWjuY6xNQgKFZ1e5LyYRGvJLmVTjLzUMhm+1Rq6KCoa+up3zw9lrrBp7Tmf7wdxIG/J25Ukm1oTFpPU+ktF6xUElNt4Z4BTMaATcMbEAMmvabbM2tkQFyuLvZm9zwbpK0tourmxUFO5r8RMkzfs45eeGG2Zub4jhJ5G910U1JbmU2nscVI3I+C1KGGpJCAIAgCAIAgLgumLuiArAIC4Fb05cCGVWhAQGbo/SskGQ+JnZdw/CeC3o4mdLRarkc1fCwravR8/ub2n07C/eSw/fGXqMl6NPHUpb6Hm1MBVjtr5Gxp6tpzZI3/A4foV0Z6dRbp/E5ZU5x7yZPJO9ws5ziPvEke6mNKnB3jFLyRQhfI1u8geJsrOUVuyVFvZGFPpiBn+8B7mfF+WS554yjHjfyOiGDrS/rbz0NPXafe+4jGAcz83lwHuuGtjpT0hp8z0KPR8Y6zd/l+TULiR3hAUJVJysgWrnLBAFDdlcEkO7zXIy6MpfRnGEBZNuKrPYtHcx1iahAUKzq9yXkwiNeSXM2kHw+aqyrOg0Zq3JLZ0l42d/znwHDz9Fy1MVGOkdWcFfHwhpHV/A6H9kQMZgEbSCRfFmSRexJ33Fz4cFx9dNyvc81YmrKeZyNFpDVwi7oTcdl2/yPHz91108SnpI9Gjjk9KnvOfqIy0OBBBANwciMuIXUmnsd8WnqjXK5cIAgCAIAgCAqFaMsrBVdKdyAgCAqCtY1OZFi5app7EBSBZLAtLQoyk3GAcgoyjMxgCnKLsrZLEFVICN2BQlZSqcibFqybuSFACN2BQlc855iSWHd5rNlkX7Y9y97rGc+RDbHuTrGMiKOkJyyUObZKikWKpYIChWdXuS8mERryS5vtWdLQ05+0jub5P3lvgDl6Z+K5sRSnNdl+hxYzD1Kq7EvTmd9TVLJWhzHBzTxb+vIry5RcXZo8GcJQdpKzKz7vNTEQ3IHuDQSSABvJyA8VdK5qk27I5LWTTMEgLGND3Wtj3YfDifyXdQozjq36Hq4TD1IPNJ2XI5ZdZ6IQBAEAQBAEAQFVKk1sCt1tGonuRYLQBAEBW6upyRAurKq+QsVup61Cwup61CwunWoWF1XrfAWKXVXUkxYoq3JNtqwaLrDOvic0/Hq9r3uLY+ODffD8XJZ1M2Xs7lo2vqdB0ku0KXt/Zgkx2GPBcU9rfwh/wAWPde2XndZUOt/v+S07HE3WsqiRmUWMpNklFUE0O7zUMsii9syCAIAgCAoVnV7kvJhEa8kuEBk0NdJA7FG8tPduP4huKrOEZq0kZ1KUKitNXOlj10vH8cV5BuwmzD3m+bfdcfsfa0eh5r6LtPsy0+P77jn9I6VmqD8bsuDW5NHlx811QpRhsehSoQpLsr14mCtDYIAgCAlj3K8dikty5WKhAEAQECyNQgKqVJrYC60VV8SLFbq6qRFgrKS5gKQEAQBAEAUZkBdVdSIsUuqOryFgqOTe5JRVAQBATQ7vNQyyJ9gO9ezcyGwHelwNgO9LgbAd6XA2A70uBsB3rOq+xLyZK3HVG8z7fReTmNLDqjeZ9vomYWHVG8z7fRMwsOqN5n2+iZhYdUbzPt9EzCw6o3mfb6JmFh1RvM+30TMLDqjeZ9vomYWHVG8z7fRMwsSMpW23lWjLQq4ou6q3mVbMyMqHVW8ymZjKh1VvMpmYyodVbzKZmMqIeqN5n2+iyzF7DqjeZ9vopzCw6o3mfb6JmFh1RvM+30TMLDqjeZ9vomYWHVG8z7fRRmFh1RvM+30U5hYdUbzd/XkmdiyHVG83f15Kc8hlQ6o3m7+vJRnYsh1RvM+30TMxYdUbzPt9FGYWHVG8z7fRTmFh1RvM+30TMLDqjeZ9vomYWHVG8z7fRMwsOqN5n2+iZhYdUbzPt9EzCxJHSttvKi5Nj//2Q==)

# Table of Content
1. [MongoDB Overview](#mongodb)
2. [Why Use MongoDB](#why-use-mongodb)
3. [Use Cases](#use-cases)
4. [MongoDB Architecture](#mongodb-architecture)
5. [Data Modeling in MongoDB](#data-modeling-in-mongodb)
6. [Indexing in MongoDB](#indexing-in-mongodb)
7. [Installing MongoDB](#installing-mongodb)
8. [Using MongoDB](#using-mongodb)
9. [Reference](#Reference)

# MongoDB

- MongoDB is a document based database, which internally stores data in the form of
BSON, but we as normal developers can send or receive data in form of JSON,
internally mongodb manages the conversion of JSON-BSON and BSON-JSON
automatically.

- Now when we used to store data in any RDBMS say MySQL, data was stored in tables.
Tables used to represent real life entity. Inside a table, we had many rows. Rows used
to represent one data record. Columns inside table used to represent properties of the
entity.

- Now in mongodb, we store data in form of documents (JSON like).
So here, a real life entity is represented by Collections. What table is for RDBMS is
collections for mongodb. In simple terms, collections are group of JSON documents.
One record in a collection is called as Document. What row is for RDBMS is document
for mongodb.

- A document is nothing but a JSON (internally BSON), a JSON has multiple key-value
pairs. The key of JSON represent the property of the entity. So what column is for
RDBMS, key (from key-value pair) is for mongodb .

# Why use MongoDB

- **Flexible Schema** : MongoDB's document-based model allows for dynamic and flexible schemas, enabling developers to store data of varying structures without needing a predefined schema.
- **Scalability** : MongoDB is designed to scale horizontally across multiple servers, making it suitable for applications with growing data needs.
- **High Performance** : MongoDB's architecture and query optimization techniques result in high performance and low latency, even for large datasets.
- **Rich Query Language** : MongoDB Query Language (MQL) supports powerful queries, including complex aggregations and geospatial queries, allowing for efficient data retrieval.
- **Replication and High Availability**: MongoDB offers built-in replication features to ensure data redundancy and fault tolerance, providing high availability and disaster recovery capabilities.
- **Automatic Sharding**: MongoDB can automatically distribute data across multiple nodes using sharding, enabling horizontal scaling and improved performance.
- **Community Support and Ecosystem**: MongoDB has a vibrant community and a rich ecosystem of tools, libraries, and integrations, making it easy to develop and maintain MongoDB-based applications.

# Use Cases
**Content Management Systems (CMS)**:

- MongoDB's flexible schema is well-suited for managing content in CMS platforms where content structures may vary widely.
- It allows for easy storage and retrieval of multimedia content, such as text, images, and videos.
Example: A news website that needs to store articles, images, and videos with different metadata.
Real-Time Analytics:

- MongoDB's high scalability and real-time data processing capabilities make it ideal for real-time analytics applications.
- It can handle large volumes of data and provide insights into user behavior, trends, and patterns.
Example: A social media platform analyzing user interactions and engagement in real-time.

**Internet of Things (IoT) Data Management**:

- MongoDB's ability to handle diverse data types and its scalability make it suitable for managing IoT data.
- It can store sensor data, device logs, and telemetry data from millions of connected devices.
Example: Smart city projects collecting and analyzing data from sensors deployed across the city for traffic management or environmental monitoring.
Catalog and Product Management:

- MongoDB's document model allows for easy representation of product catalogs with varying attributes and categories.
- It can efficiently manage product information, inventory, and customer reviews.
Example: E-commerce platforms managing product catalogs with millions of products and multiple attributes.
Mobile and Web Applications:

- MongoDB's JSON-like document structure aligns well with the data formats used in mobile and web applications.
- It provides seamless integration with popular programming languages and frameworks.
Example: Mobile applications requiring offline sync and real-time data updates, such as messaging apps or collaborative task managers.
User Profiles and Personalization:

- MongoDB's flexible schema allows for storing and managing user profiles with varying attributes and preferences.
- It can power personalized experiences by storing user preferences, interaction history, and recommendations.
Example: Online platforms delivering personalized content recommendations based on user behavior and preferences.

**Real-Time Analytics**:

- MongoDB's high scalability and real-time data processing capabilities make it ideal for real-time analytics applications.
It can handle large volumes of data and provide insights into user behavior, trends, and patterns.
Example: A social media platform analyzing user interactions and engagement in real-time.
Internet of Things (IoT) Data Management:

- MongoDB's ability to handle diverse data types and its scalability make it suitable for managing IoT data.
It can store sensor data, device logs, and telemetry data from millions of connected devices.
Example: Smart city projects collecting and analyzing data from sensors deployed across the city for traffic management or environmental monitoring.



 ## MongoDB Architecture

 Sure, let's break down each component of MongoDB architecture in simple terms:

### Database:
Think of a database as a big container where you can store different sets of information. It's like a folder on your computer where you keep files related to a specific topic. In MongoDB, a database is where you organize your collections.

### Collection:
A collection is like a folder inside a database. It's where you group similar types of documents together. For example, if you're storing information about different types of animals, you might have a collection called "Animals" where each document represents a different animal.

### Document:
A document is like a single file within a collection. It's where you store specific pieces of information about one thing. Going back to the animal example, each document in the "Animals" collection might represent a different animal, with details like its name, species, age, etc. Documents are like rows in a spreadsheet, but they can hold more complex data.

### Field:
A field is like a label on a piece of information within a document. It's the key part of a key-value pair. For instance, in our animal document, "name" might be a field with the value "Lion", "species" might be a field with the value "Panthera leo", and so on. Fields help organize and describe the data within a document.

### Index:
An index is like a quick reference guide for finding specific information within your documents. Just like an index in a book helps you quickly locate a particular topic, an index in MongoDB helps speed up the process of finding data. It's a data structure that MongoDB uses to optimize search and retrieval operations, making your queries run faster.

## Data Modeling in MongoDB

Let's break down data modeling in MongoDB into simple terms:

### Designing MongoDB schemas based on application requirements:
- **Schema:** Think of a schema as a blueprint or plan for how your data will be organized in MongoDB. It defines the structure of your documents, including what fields they will have and what types of data those fields can hold.
- **Application requirements:** This refers to what your application needs to do and how it needs to store and retrieve data. For example, if you're building a social media app, you might need to store user profiles, posts, comments, etc. Your schema should be designed to support these requirements efficiently.

### Embedding vs. Referencing data:
- **Embedding:** Embedding means putting one piece of data inside another. In MongoDB, you can embed documents within other documents. For example, if you have a blog post document, you might embed the comments for that post directly within the post document. This can be useful when the embedded data is small and doesn't change frequently.
- **Referencing:** Referencing means storing a reference or link to another document instead of embedding it directly. For example, instead of embedding comments within a blog post document, you might store the IDs of the comments and then retrieve the comments separately when needed. This can be useful when the referenced data is large or changes frequently.

### Understanding MongoDB's flexible schema:
- **Flexible schema:** Unlike traditional relational databases, MongoDB has a flexible schema, which means that documents in the same collection don't have to have the same structure. This allows you to store different types of data together and easily modify the schema as your application evolves.
- **Benefits:** The flexible schema makes MongoDB agile and adaptable to changing requirements. It allows you to iterate quickly during development and easily accommodate new features or data types without having to redesign your entire database schema.

## Querying in MongoDB
Let's simplify querying in MongoDB:

### CRUD Operations: Create, Read, Update, Delete
- **Create:** Adding new data to your MongoDB database. It's like adding a new record to your list of contacts or creating a new document in your database.
- **Read:** Retrieving existing data from your MongoDB database. It's like looking up a phone number in your contacts or reading a book from your library.
- **Update:** Changing existing data in your MongoDB database. It's like editing a contact's information or updating a book's description.
- **Delete:** Removing data from your MongoDB database. It's like deleting a contact from your list or returning a borrowed book to the library.

### Query Operators: $eq, $gt, $lt, $in, $and, $or, etc.
- **$eq:** Matches values that are equal to a specified value. For example, finding all documents where the "age" field equals 30.
- **$gt:** Matches values that are greater than a specified value. For example, finding all documents where the "price" field is greater than 100.
- **$lt:** Matches values that are less than a specified value. For example, finding all documents where the "quantity" field is less than 10.
- **$in:** Matches any of the values specified in an array. For example, finding all documents where the "status" field is either "open" or "pending".
- **$and:** Combines multiple conditions, all of which must be true for a document to be included in the results. For example, finding all documents where the "age" is greater than 18 and the "gender" is "female".
- **$or:** Matches any of the specified conditions, where at least one condition must be true for a document to be included in the results. For example, finding all documents where the "category" is either "electronics" or "clothing".

### Projection and Aggregation
- **Projection:** It allows you to specify which fields to include or exclude from the query results. For example, retrieving only the "name" and "email" fields from a collection of user documents.
- **Aggregation:** Aggregation operations allow you to process and analyze data in MongoDB, such as calculating averages, grouping data, and performing calculations across multiple documents. For example, calculating the total sales revenue for a specific product category.

## Indexing in MongoDB

Let's simplify indexing in MongoDB:

### Types of Indexes:
- **Single-field Index:** Indexes a single field in a document. It's like creating an index for the "last name" column in a phone book to quickly find people by their last names.
- **Compound Index:** Indexes multiple fields together. It's like creating an index for both "last name" and "first name" columns in a phone book to find people by their full names more efficiently.
- **Multikey Index:** Indexes arrays in documents. It's like creating an index for the "hobbies" field, which contains multiple hobbies for each person in a document, allowing you to quickly find people based on their hobbies.
- **Text Index:** Special index type optimized for searching text content. It's like creating an index for the "description" field in a collection of articles to quickly find articles containing specific keywords.
- **Hashed Index:** Hashes the values of indexed fields. It's like creating an index for the "password" field in a user database to securely store and retrieve passwords.
- **Geospatial Index:** Indexes geographical data. It's like creating an index for the "location" field in a collection of restaurants to quickly find nearby restaurants based on coordinates.

### Index Creation and Management:
- **Creating Indexes:** In MongoDB, you can create indexes using the createIndex() method. You specify the fields to index and any additional options, such as unique constraints or index type.
- **Managing Indexes:** MongoDB provides commands and methods to manage indexes, such as dropping indexes, listing existing indexes, and modifying index options. This allows you to optimize your database performance as your application evolves.

### Indexing Strategies for Optimal Performance:
- **Identify Query Patterns:** Understand the common queries your application performs and create indexes that support those queries. For example, if your application frequently searches for documents by a specific field, create an index on that field.
- **Avoid Over-Indexing:** While indexes can improve query performance, they also consume storage space and can slow down write operations. Avoid creating indexes on fields that are rarely queried or don't significantly improve query performance.
- **Monitor and Tune Indexes:** Regularly monitor your database performance and index usage. Adjust your indexing strategy based on changes in query patterns or performance issues. Consider using tools like MongoDB's Database Profiler to identify slow queries and optimize index usage.

# Installing MongoDB
To install mongoDb your system need to download
```
Link: https://medium.com/@LondonAppBrewery/how-to-download-install-mongodb-on-
windows-4ee4b3493514
```
# Using MongoDB

Open MongoDB in terminal:
Write  ``mongosh``  in your terminal, and it will open the mongodb console.


# List all databases in mongodb

To list all the databases stored in your mongodb we can use the below commands:

```
show database;
```
or

```
show dbs;
```

# How to select a particular DB to work on?

To select a particular db and start querying on it we can use
```
use name_of_database;
```


# How to print all the collections stored in a database ?

To print all the collections we can use:
```
show collections;
```


# How to print all the documents of a collection ?

To print all the documents of a collection we can use:
```
db.collectionname.find();
```

# How to create a new database ?
To create a new database we can do:
```
use new_database_name;
```
The ```use``` command creates a new database if there is no already present db with the
same name, otherwise if there is a db with the same name, it just selects it.

Now what will happen is, after creating a DB, if we try to do show dbs; then it will not list
our newly created database. Because, if mondodb sees that there is no valid collection
added in the database, and the db is empty, it doesn’t list it.

# How to add a new collections ?
To create a new collection we can do:
```
db.createCollection("name_of_the_collection")
```
Make sure we execute this command after use some_db_name

In normal RDBMS, while create a table, we have to define what will be the column of
the table. Why we are not defining properties of a collection on mongodb ?
This is because, mongodb doesn’t restrict us by any means for defining documents of a
collection. Two documents of the same collection can posses different type of
properties.

# How to add a new record to a collection ?
To add a new record we can do:
```
db.collectionName.insertOne({key1: value1, key2: value2 ....})
```
## Reference 
-  https://en.wikipedia.org/wiki/MongoDB 
-  https://www.w3schools.com/mongodb/
-  https://www.ibm.com/topics/mongodb
-  https://www.mongodb.com/docs/
