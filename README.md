# Package providing the /snap directory

The purpose of this package is to contain a symbolic link from `/snap` to
`/var/lib/snapd/snap`. This is only necessary for snaps that are using classic
confinement as regular snaps that rely on the execution environment crafted by
snap-confine are not affected.
