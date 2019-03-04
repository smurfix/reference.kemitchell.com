---
title: Intentional Weakening of Strong-Copyleft Licenses
---

## GPL Linking Exception, esp. classpath

> Linking this library statically or dynamically with other modules is making a combined work based on this library. Thus, the terms and conditions of the GNU General Public License cover the whole combination.
>
> As a special exception, the copyright holders of this library give you permission to link this library with independent modules to produce an executable, regardless of the license terms of these independent modules, and to copy and distribute the resulting executable under terms of your choice, provided that you also meet, for each linked independent module, the terms and conditions of the license of that module. An independent module is a module which is not derived from or based on this library. If you modify this library, you may extend this exception to your version of the library, but you are not obligated to do so. If you do not wish to do so, delete this exception statement from your version.

## GCC Runtime Library Exception, for libgcc

### 2.0

> In addition to the permissions in the GNU Library General Public License, the Free Software Foundation gives you unlimited permission to link the compiled version of this file into combinations with other programs, and to distribute those programs without any restriction coming from the use of this file. (The General Public License restrictions do apply in other respects; for example, they cover modification of the file, and distribution when not linked into another program.)

### 3.1

> GCC RUNTIME LIBRARY EXCEPTION
>
> Version 3.1, 31 March 2009
>
> General information: http://www.gnu.org/licenses/gcc-exception.html
>
> Copyright (C) 2009 Free Software Foundation, Inc. <http://fsf.org/>
>
> Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed. 
>
> This GCC Runtime Library Exception ("Exception") is an additional permission under section 7 of the GNU General Public License, version 3 ("GPLv3"). It applies to a given file (the "Runtime Library") that bears a notice placed by the copyright holder of the file stating that the file is governed by GPLv3 along with this Exception.
>
> When you use GCC to compile a program, GCC may combine portions of certain GCC header files and runtime libraries with the compiled program. The purpose of this Exception is to allow compilation of non-GPL (including proprietary) programs to use, in this way, the header files and runtime libraries covered by this Exception.
>
> 0\. Definitions.
>
> A file is an "Independent Module" if it either requires the Runtime Library for execution after a Compilation Process, or makes use of an interface provided by the Runtime Library, but is not otherwise based on the Runtime Library.
>
> "GCC" means a version of the GNU Compiler Collection, with or without modifications, governed by version 3 (or a specified later version) of the GNU General Public License (GPL) with the option of using any subsequent versions published by the FSF.
>
> "GPL-compatible Software" is software whose conditions of propagation, modification and use would permit combination with GCC in accord with the license of GCC.
>
> "Target Code" refers to output from any compiler for a real or virtual target processor architecture, in executable form or suitable for input to an assembler, loader, linker and/or execution phase. Notwithstanding that, Target Code does not include data in any format that is used as a compiler intermediate representation, or used for producing a compiler intermediate representation.
>
> The "Compilation Process" transforms code entirely represented in non-intermediate languages designed for human-written code, and/or in Java Virtual Machine byte code, into Target Code. Thus, for example, use of source code generators and preprocessors need not be considered part of the Compilation Process, since the Compilation Process can be understood as starting with the output of the generators or preprocessors.
>
> A Compilation Process is "Eligible" if it is done using GCC, alone or with other GPL-compatible software, or if it is done without using any work based on GCC. For example, using non-GPL-compatible Software to optimize any GCC intermediate representations would not qualify as an Eligible Compilation Process.
>
> 1\. Grant of Additional Permission.
>
> You have permission to propagate a work of Target Code formed by combining the Runtime Library with Independent Modules, even if such propagation would otherwise violate the terms of GPLv3, provided that all Target Code was generated by Eligible Compilation Processes. You may then convey such a combination under terms of your choice, consistent with the licensing of the Independent Modules.
>
> 2\. No Weakening of GCC Copyleft.
>
> The availability of this Exception does not imply any general presumption that third-party software is unaffected by the copyleft requirements of the license of GCC.

## MongoDB AGPL clarification

<https://www.mongodb.com/blog/post/the-agpl>

> MongoDB is released under the <a href="http://www.fsf.org/licensing/licenses/agpl-3.0.html">GNU Affero General Public License</a>.  This Free Software Foundation license is fairly new, and thus we wanted to talk about how this license differs from GPL.
>
> Our goal with using AGPL is to preserve the concept of <a href="http://www.fsf.org/licensing/essays/copyleft.html">copyleft</a> with MongoDB.  With traditional <a href="http://www.gnu.org/copyleft/gpl.html">GPL</a>, copyleft was associated with the concept of distribution of software.  The problem is that nowadays, distribution of software is rare: things tend to run in the cloud.  AGPL fixes this “loophole” in GPL by saying that if you use the software over a network, you are bound by the copyleft.  Other than that, the license is virtually the same as GPL v3.
>
> To say this another way: if you modify the core database source code, the goal is that you have to contribute those modifications back to the community.
>
> Note however that it is NOT required that applications using mongo be published.  The copyleft applies only to the mongod and mongos database programs.  This is why Mongo DB drivers are all licensed under an <a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache license</a>.  You application, even though it talks to the database, is a separate program and “work”.
>
> As always, we want your feedback (and participation) – comments welcome both here and in the <a href="http://groups.google.com/group/mongodb-user">forums</a>.

## MongoDB SSPL FAQ

<https://www.mongodb.com/licensing/server-side-public-license/faq#implications>

> What are the implications of the SSPL on applications built using MongoDB and made available as a service (SaaS)?
>
> The copyleft condition of Section 13 of the SSPL applies only when you are offering the functionality of MongoDB, or modified versions of MongoDB, to third parties as a service. There is no copyleft condition for other SaaS applications that use MongoDB as a database.

## Linux Syscall Note

> NOTE! This copyright does *not* cover user programs that use kernel
> services by normal system calls - this is merely considered normal use
> of the kernel, and does *not* fall under the heading of "derived work".
> Also note that the GPL below is copyrighted by the Free Software
> Foundation, but the instance of code that it refers to (the Linux
> kernel) is copyrighted by me and others who actually wrote it.
>
> Also note that the only valid version of the GPL as far as the kernel
> is concerned is _this_ particular version of the license (ie v2, not
> v2.2 or v3.x or whatever), unless explicitly otherwise stated.

## GPL Cooperation Commitment

<https://gplcc.github.io/gplcc/>

## The Principles of Community-Oriented GPL Enforcement

<https://www.fsf.org/licensing/enforcement-principles>

<https://sfconservancy.org/copyleft-compliance/principles.html>

## Totem GStreamer Plugin Exception

> The Totem project hereby grants permission for non-GPL compatible
> GStreamer plugins to be used and distributed together with GStreamer and
> Totem. This permission is above and beyond the permissions granted by
> the GPL license by which Totem is covered. If you modify this code, you may
> extend this exception to your version of the code, but you are not obligated
> to do so. If you do not wish to do so, delete this exception statement from
> your version.

<https://gstreamer.freedesktop.org/documentation/application-development/appendix/licensing.html>