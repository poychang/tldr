# kosmorro

> Compute the ephemerides and the events for a date at a position on Earth.
> More information: <https://kosmorro.space>.

- Get ephemerides for Paris, France:

`kosmorro --latitude={{48.7996}} --longitude={{2.3511}}`

- Get ephemerides for Paris, France, in the UTC+2 timezone:

`kosmorro --latitude={{48.7996}} --longitude={{2.3511}} --timezone={{2}}`

- Get ephemerides for Paris, France, on June 9th, 2020:

`kosmorro --latitude={{48.7996}} --longitude={{2.3511}} --date={{2020-06-09}}`

- Generate a PDF (Note: TeXLive must be installed):

`kosmorro --format={{pdf}} --output={{path/to/file.pdf}}`
